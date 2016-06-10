# Ansible Role for Apache Maven

Installs Apache Maven for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    maven_version: 3.3.9
    maven_download_dir: /tmp
    maven_install_dir: /opt

## Dependencies

None.

## Example Playbook

For RHEL / CentOS

```yaml
---
- hosts: localhost
  remote_user: root
  roles:
    - ansible-role-maven
```
## License

MIT

## Author Information

This role was created by Alexander Wolff.
