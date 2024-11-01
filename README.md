🐍 jiholland.python
===================

Build, compile, and altinstall Python from source code on a system with Python already installed.

Requirements
------------

- [Community General Collection](https://galaxy.ansible.com/ui/repo/published/community/general)

Role Variables
--------------

- python_version
- python_url
- python_prefix

Dependencies
------------

None.

Example Playbook
----------------
```YAML
---
- name: Download, build, compile, and altinstall Python from source code.
  gather_facts: true
  hosts: localhost
  roles:
    - role: python
      vars:
        python_version: "3.12.7"
```
License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
