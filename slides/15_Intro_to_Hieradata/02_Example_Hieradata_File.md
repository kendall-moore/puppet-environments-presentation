## Example Hieradata Configuration File

```
# An example to setup NTP in common.yaml
---
ntp::restrict:
  -
ntp::autoupdate: false
ntp::enable: true
ntp::servers:
  - 0.us.pool.ntp.org iburst
  - 1.us.pool.ntp.org iburst
  - 2.us.pool.ntp.org iburst
  - 3.us.pool.ntp.org iburst
```
