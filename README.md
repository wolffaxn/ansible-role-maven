# Ansible Role - Apache Maven

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/wolffaxn/ansible-role-maven/master/LICENSE)

Installs Apache Maven for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    maven_version: 3.5.0

    maven_download_dir: /tmp
    maven_download_cleanup: true
    maven_install_dir: /opt

    maven_set_maven_home: true

## Dependencies

None.

## Example Playbook

For RHEL / CentOS

```yaml
---
- hosts: localhost
  become: true
  become_method: sudo
  remote_user: root
  roles:
    - ansible-role-maven
```
## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file.
