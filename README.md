Vector
=========

This role can install Vector on Centos

Role Variables
--------------

| vars | description |
| --- | --- |
| vector_version | Version of Vector to install |
| vector_config | Config of Vector (yaml) |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Andrey Zemlyachev
