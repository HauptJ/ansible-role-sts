Ansible role: Spring Tool Suite
=========

[![Build Status](https://travis-ci.org/by-erik/ansible-role-sts.svg?branch=master)](https://travis-ci.org/by-erik/ansible-role-sts)

Ansible role for installing the Spring Tool Suite.

Requirements
------------

Local

* Ansible >= 2.4

Remote

* Ubuntu 16.04

Role Variables
--------------

```yaml
sts_dest: '/opt' # Where should the STS be installed
```

Example Playbook
----------------

Minimal:
```yaml
- hosts: servers
  roles:
    - role: by-erik.sts
```

With specifying the dest:
```yaml
- hosts: servers
  roles:
    - role: by-erik.sts
      sts_dest: '/opt' # Default
```

License
-------

MIT License

Author Information
------------------

Erik H.
