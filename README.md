🐍 jiholland.python
===================

Build, compile, and install Python from source code.

Requirements
------------

- [Community General Collection](https://galaxy.ansible.com/ui/repo/published/community/general)

Role Variables
--------------

- python_version
- python_archive_format
- python_url
- python_install_prefix

Dependencies
------------

None.

Example Playbook
----------------
```YAML
---
- name: Download, build, compile, and install Python from source code.
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
