setupmyBox
=========

An ansible playbook to install some dependecies for fresh install virtual machine.

Features
------------

1. Upgrade all packages in OS
2. Setup Proxy for apt and system wide
3. Install Docker
4. Install Kubernets packages
5. Reboot System if needed
6. ...


Role Variables
--------------

Before running playbook, please specify variables in `defaults/main.yml`


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: localhost
  become: true
  roles:
    - setupmyBox

```



![Ubuntu](https://github.com/danitfk/setupmyBox/blob/master/.github/ubuntu.png?raw=true)  ![Ansible](https://github.com/danitfk/setupmyBox/blob/master/.github/ansible.png?raw=true)  ![Docker](https://github.com/danitfk/setupmyBox/blob/master/.github/docker.png?raw=true)  ![Kubernetes](https://github.com/danitfk/setupmyBox/blob/master/.github/kubernetes.png?raw=true)
