Role Name
=========

Debian Jessie base setup.

Role Variables
--------------

```yaml
debian-jessie_manager_account: YOUR_MANAGER_ACCOUNT
debian-jessie_manager_group: YOUR_MANAGER_GROUP
debian-jessie_manager_password: YOUR_MANAGER_PASSWORD
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: evannook.debian-jessie }
      vars:
         debian-jessie_manager_account: YOUR_MANAGER_ACCOUNT
         debian-jessie_manager_group: YOUR_MANAGER_GROUP
         debian-jessie_manager_password: YOUR_MANAGER_PASSWORD

License
-------

MIT

Author Information
------------------

Evan Nook
