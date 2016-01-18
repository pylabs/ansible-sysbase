sysbase
=======

Debian base system setup.

Role Variables
--------------

```yaml
sysbase_manager_account: YOUR_MANAGER_ACCOUNT
sysbase_manager_group: YOUR_MANAGER_GROUP
sysbase_manager_password: YOUR_MANAGER_PASSWORD
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: evannook.sysbase
  vars:
     sysbase_manager_account: YOUR_MANAGER_ACCOUNT
     sysbase_manager_group: YOUR_MANAGER_GROUP
     sysbase_manager_password: YOUR_MANAGER_PASSWORD
```

License
-------

MIT

Author Information
------------------

Evan Nook
