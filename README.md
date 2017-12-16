# node

[![Build Status](https://travis-ci.org/pyslackers/ansible-role-node.svg?branch=master)](https://travis-ci.org/pyslackers/ansible-role-node)

Ansible role to install NodeJS.

## Role Variables

* `version`: The node version to install - should be either `8` or `9`, defaults to 8

## Dependencies

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - role: pyslackers.node
      version: '8'
```

## License

> MIT
