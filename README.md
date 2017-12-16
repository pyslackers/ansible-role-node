# node

Ansible role to install and configure NodeJS.

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
