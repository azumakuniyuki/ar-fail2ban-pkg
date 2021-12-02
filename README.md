Ansible Role: Fail2Ban(pkg)
================================================================================
Install and configure Fail2Ban

- Install Fail2Ban
- Configure files in /etc/fail2ban

Requirements
--------------------------------------------------------------------------------
None

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
fail2ban:
  enabled: true
  started: true
  serverroot: "/etc/fail2ban"
  configroot: "/etc/fail2ban"
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-fail2ban-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

