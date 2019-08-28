# Ansible Role - Apache Maven

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/wolffaxn/ansible-role-maven/master.svg)](https://github.com/wolffaxn/ansible-role-maven)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [About](#about)
- [Requirements](#requirements)
- [Role Variables](#role-variables)
- [Dependencies](#dependencies)
- [Example Playbook](#example-playbook)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

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
