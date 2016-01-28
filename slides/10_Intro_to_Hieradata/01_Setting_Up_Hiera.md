## Setting Up Hiera

```
# A basic setup for /etc/puppet/hiera.yaml
---
:backends:
  - yaml
  - eyaml
:yaml:
  :datadir: /etc/puppet/environments/%{environment}/hieradata
:eyaml:
  :datadir: /etc/puppet/environments/%{environment}/hieradata/encrypted
  :pkcs7_private_key: /etc/puppet/keys//private_key.pkcs7.pem
  :pkcs7_public_key:  /etc/puppet/keys/public_key.pkcs7.pem
:hierarchy:
  - "node/%{::fqdn}"
  - "%{::osfamily}"
  - common
```
