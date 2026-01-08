ansible-terraform
==============

An Ansible role to install terraform.

Supported platfroms:
```
- Debian 12 (Bookworm)
- Debian 13 (Trixie)
- Ubuntu 22.04 (Jammy Jellyfish)
- Ubuntu 24.04 (Noble Numbat)
```

Requirements
------------

This role requires Ansible 2.19 or higher

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  gather_facts: true
  roles:
    - serhii9132.terraform
```

License
-------

MIT
