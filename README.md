sysbase
=======

Debian base system setup.

Role Variables
--------------

```yaml
sysbase_manager_account: YOUR_MANAGER_ACCOUNT
sysbase_manager_group: YOUR_MANAGER_GROUP
sysbase_manager_password: YOUR_MANAGER_PASSWORD
sysbase_dns_servers: (optional)
  - A LIST OF
  - DNS SERVER IP
sysbase_timezone: YOUR_TIMEZONE_NAME
sysbase_locale: YOUR_LOCALE_NAME
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: pylabs.sysbase
  vars:
     sysbase_manager_account: john
     sysbase_manager_group: john
     sysbase_manager_password: john_password
     sysbase_dns_servers:
       - 8.8.8.8
       - 8.8.4.4
     sysbase_timezone: Asia/Taipei
     sysbase_locale: en_US.UTF-8
```

License
-------

MIT

Author Information
------------------

William Wu <william@pylabs.org>
