[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-timesync.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-timesync)

# lifeofguenter.timesync

Network Time Synchronization (NTP) via time.google.com

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

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[Gunter Grodotzki](https://lifeofguenter.de)
