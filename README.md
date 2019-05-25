setupmyBox
=========

An ansible playbook to install some dependecies for fresh install virtual machine.

Features
------------

1. Upgrade all packages in OS
2. Setup Proxy for apt and system wide
3. Install Docker
4. Reboot System if needed
5. ...


Role Variables
--------------

Before running playbook, please specify variables in `defaults/main.yml`


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: localhost
  remote_user: root
  roles:
    - setupmyBox

```


