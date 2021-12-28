# lifeofguenter.timesync

[![Build Status](https://travis-ci.com/lifeofguenter/ansible-role-timesync.svg?branch=main)](https://travis-ci.com/lifeofguenter/ansible-role-timesync)

Network Time Synchronization (NTP) via time.google.com on Debian-like systems

## Requirements

systemd

## Role Variables

```yaml
timesync_explicit_disable: false

timesync_servers:
  - time.google.com
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: lifeofguenter.timesync }
```

## License

**MIT**, see the [LICENSE file](LICENSE) for details.

## Author Information

[Günter Grodotzki](https://www.lifeofguenter.de)
