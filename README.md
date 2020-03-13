Ansible role for valgrind
==================================

Installs valgrind

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-valgrind/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-valgrind/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-valgrind/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-valgrind/actions?query=workflow%3A%22Release%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `valgrind_version` | Verson of valgrind to install | string | `3.15.0` | true |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-valgrind
      vars:
        valgrind_version: 3.15.0
```

License
-------

[Apache License](LICENSE)
