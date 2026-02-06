=======
lighthouse-role
=========

Installs Lighthouse.

Requirements
------------

- Ansible 2.9 или выше
- Node.js (версии, совместимые с Lighthouse)

Role Variables
--------------

|-------------------------------|----------------------------------------------|
|   lighthouse_vcs              | repo address                                 |
|   lighthouse_dir              | lighthouse dir (/var/lib/lighthouse)         |
|   lighthouse_access_log_name  | a name for lighthouse access log             |
|   lighthouse_version          | version                                      |
|-------------------------------+----------------------------------------------|

Dependencies
------------

There are no dependencies for the role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
    - role: Lighthouse-role
      lighthouse_version: "8.0.0"
```
License
-------

MIT

Author Information
------------------

Vladimir Inshakov