# lifeofguenter.timesync

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/lifeofguenter/ansible-role-timesync/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/lifeofguenter/ansible-role-timesync/tree/main)

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
