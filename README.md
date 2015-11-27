ansible
=======

[![Ansible Role](https://img.shields.io/ansible/role/6257.svg)](https://galaxy.ansible.com/list#/roles/6257)

Installs Ansible

Requirements
------------

This role requires Ansible 1.6 or higher.

Role Variables
--------------

| Name                    | Default | Description                   |
|-------------------------|---------|-------------------------------|
| ansible_install_version | 1.9.4   | Version of Ansible to install |

Dependencies
------------

None

Example Playbook
----------------

Install Ansible
```
- hosts: all
  roles:
    - kbrebanov.ansible
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
