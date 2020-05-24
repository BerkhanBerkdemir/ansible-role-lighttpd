# Ansible role for Lighttpd

Installs, configures, and manages Lighttpd virtual hosts, web services, and
modules.

## Requirements

This role does not require any extra Python package other than `ansible` 2.7
and up.

## Role Variables

* `lighttpd_version` (default: `1.4.53-4`): installable Lighttpd version with
  `apt-get` utility.

## Dependencies

There is not role or collection dependency for this Ansible role.

## Example Playbook

The simplest way to use this Ansible role is to add as role with no additional
variables. This will give you the latest Lighttpd set-up with PHP FPM, SSL
configuration and as well as firewall and systemd configuration.

```yaml
- hosts: servers
  roles:
     - berkhanberkdemir.ansible-role-lighttpd
```

## License

BSD 2-Clause "Simplified" License
