# apache

Ansible role to install and configure Apache http server.

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

```sh
git submodule add https://git.sekoya.org/mb/apache.git roles/apache
```

## Example Playbook

    - hosts: servers
      roles:
         - apache


    - hosts: servers
      roles:
         - { role: apache, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
