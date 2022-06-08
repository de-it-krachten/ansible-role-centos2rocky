[![CI](https://github.com/de-it-krachten/ansible-role-centos2rocky/workflows/CI/badge.svg?event=push)](https://github.com/de-it-krachten/ansible-role-centos2rocky/actions?query=workflow%3ACI)


# ansible-role-centos2rocky

Role to migrate fron CentOS 8 -> RockyLinux 8 


Platforms
--------------

Supported platforms

- CentOS 8

Note:
<sup>1</sup> : no automated testing is performed on these platforms

Role Variables
--------------
<pre><code>

</pre></code>


Example Playbook
----------------

<pre><code>
- name: sample playbook for role 'centos2rocky'
  hosts: all
  vars:
  tasks:
    - name: Include role 'centos2rocky'
      include_role:
        name: centos2rocky
</pre></code>
