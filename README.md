[![CI](https://github.com/de-it-krachten/ansible-role-centos2rocky/workflows/CI/badge.svg?event=push)](https://github.com/de-it-krachten/ansible-role-centos2rocky/actions?query=workflow%3ACI)


# ansible-role-centos2rocky

Role to migrate from CentOS 8 -> RockyLinux 8
It works for servers and containers



## Dependencies

#### Roles
None

#### Collections
- community.general

## Platforms

Supported platforms

- CentOS 8
- SUSE Linux Enterprise<sup>1</sup>
- openSUSE Leap 15
- Debian 12 (Bookworm)
- Fedora 37

Note:
<sup>1</sup> : no automated testing is performed on these platforms

## Role Variables
### defaults/main.yml
<pre><code>
# Patch host to latest CentOS 8 state
centos2rocky_centos_upgrade: true

# Migrate host from CentOS to RockyLinux
centos2rocky_rockylinux_migration: true
</pre></code>




## Example Playbook
### molecule/default/converge.yml
<pre><code>
- name: sample playbook for role 'centos2rocky'
  hosts: all
  become: "yes"
  tasks:
    - name: Include role 'centos2rocky'
      ansible.builtin.include_role:
        name: centos2rocky
</pre></code>
