[![CI](https://github.com/de-it-krachten/ansible-role-centos2rocky/workflows/CI/badge.svg?event=push)](https://github.com/de-it-krachten/ansible-role-centos2rocky/actions?query=workflow%3ACI)


# ansible-role-centos2rocky

Role to migrate from CentOS 8 -> RockyLinux 8
It works for servers and containers


## Platforms

Supported platforms

- CentOS 8

Note:
<sup>1</sup> : no automated testing is performed on these platforms

## Role Variables
### defaults/main.yml
<pre><code>

</pre></code>



## Example Playbook
### molecule/default/converge.yml
<pre><code>
- name: sample playbook for role 'centos2rocky'
  hosts: all
  vars:
  tasks:
    - name: Include role 'centos2rocky'
      include_role:
        name: centos2rocky
</pre></code>
