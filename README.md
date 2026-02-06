lighthouse
=========

Installs Lighthouse.

Requirements
------------

- Ansible 2.9 или выше
- Node.js (версии, совместимые с Lighthouse)

Role Variables
--------------
```
|-------------------------------|----------------------------------------------|
|   lighthouse_vcs              | repo address                                 |
|   lighthouse_dir              | lighthouse dir (/var/lib/lighthouse)         |
|   lighthouse_access_log_name  | a name for lighthouse access log             |
|   lighthouse_version          | version                                      |
|-------------------------------+----------------------------------------------|
```

Dependencies
------------

There are no dependencies for the role.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: lighthouse
      lighthouse_version: "8.0.0"
```
License
-------

MIT

Author Information
------------------

Vladimir Inshakov