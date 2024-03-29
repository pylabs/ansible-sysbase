sysbase
=======

Debian / Ubuntu base system setup.

Role Variables
--------------

```yaml
sysbase_manager_account: YOUR_MANAGER_ACCOUNT
sysbase_manager_group: YOUR_MANAGER_GROUP
sysbase_manager_password: YOUR_MANAGER_PASSWORD
sysbase_skip_apt_repo_setup: "IF_BYPASS_APT_REPO_SETUP (default: no)"
sysbase_dns_servers: (optional)
  - A LIST OF
  - DNS SERVER IP
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
     sysbase_skip_apt_repo_setup: no
     sysbase_dns_servers:
       - 8.8.8.8
       - 8.8.4.4
```

License
-------

MIT

Author Information
------------------

William Wu <william@pylabs.org>
