# ansible-role-epel

This role install epel-release package and configures epel.

## Description

Installs the `epel-release` package from yum/dnf package not downloading it from bare URL.
Imports GPG key into rpm GPG key store

## Role Tags

| Name           | Description                              |
| -------------- | ---------------------------------------- |
| `epel_all`     | Tag to run only EPEL role inside a play. |
| `epel_install` | Tag to run installation of EPEL.         |

## Dependencies

**None**

## Example Playbook


```yaml
- name: All
  hosts: all
  debugger: on_failed
  roles:
    - role: ansible-role-epel
```

## License

MIT License

## Contributors

Daniel von Essen
