lighthouse-role
=======
Role Name
=========

Lighthouse-role.

Requirements
------------

- Ansible 2.9 или выше
- Node.js (версии, совместимые с Lighthouse)

Role Variables
--------------

lighthouse_vcs: https://github.com/VKCOM/lighthouse.git
lighthouse_dir: /var/lib/lighthouse
lighthouse_access_log_name: lighthouse_access
lighthouse_version: "latest"

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