# Ansible role: Homebrew

[![Build Status](https://travis-ci.org/danbohea/ansible-role-homebrew.svg?branch=master)](https://travis-ci.org/danbohea/ansible-role-homebrew)

Installs Homebrew & Homebrew Cask on Mac OS X.

## Requirements

- Mac OS 10.9+


## Role Variables

All role default variables are listed below along with their respective default values.

```
homebrew_cask_appdir: "/Applications"
```

Not used by this role itself but provides a centralised way of storing the value for other roles that may use this role as a dependency.


## Dependencies

None.


## Example Playbook

```
- hosts: macbook
  connection: local

  roles:
    - role: ansible-role-homebrew
```

## License

MIT


## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) primarily for use with [Macsible](https://github.com/danbohea/macsible).
