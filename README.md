# Ansible Role - Apache Maven

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/wolffaxn/ansible-role-maven/master.svg)](https://github.com/wolffaxn/ansible-role-maven)

## About 

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

This project is licensed under the terms of the [MIT license](LICENSE).
