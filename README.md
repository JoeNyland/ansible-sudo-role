joenyland.sudo
=========================

[![CI](https://github.com/JoeNyland/ansible-sudo-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-sudo-role/actions/workflows/ci.yml)

Configures sudo.

Requirements
------------

None.

Role Variables
--------------

### `sudo_users`

A list of users to be allowed to run sudo commands.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - joenyland.sudo
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
