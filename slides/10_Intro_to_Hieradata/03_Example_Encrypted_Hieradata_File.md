## And Again - But With Encryption

```
# Store our admin password for our traffic snooping app
# on node with fqdn marshaller.globalsercurities.org
#
# Here, we may find this in /etc/puppet/environments/production/hieradata/enrypted/<fqdn>.eyaml
---
snooper::config::master_user: >
  ENC[PKCS7,Y22exl+OvjDe+drmik2XEeD3VQtl1uZJXFFF2NnrMXDWx0csyqLB/2NOWefv
  NBTZfOlPvMlAesyr4bUY4I5XeVbVk38XKxeriH69EFAD4CahIZlC8lkE/uDh
  jJGQfh052eonkungHIcuGKY/5sEbbZl/qufjAtp/ufor15VBJtsXt17tXP4y
  l5ZP119Fwq8xiREGOL0lVvFYJz2hZc1ppPCNG5lwuLnTekXN/OazNYpf4CMd
  /HjZFXwcXRtTlzewJLc+/gox2IfByQRhsI/AgogRfYQKocZgFb/DOZoXR7wm
  IZGeunzwhqfmEtGiqpvJJQ5wVRdzJVpTnANBA5qxeA==]
snooper::config::master_pass:
  ENC[PKCS7,Y22exl+OvjDe+drmik2XEeD3VQtl1uZJXFFF2NnrMXDWx0csyqLB/2NOWefv
  KSLFHFKJLLhfasddjfhsadkfjhAJKDHkasjhfkljSADSFHklLHDklalsfhaA
  lkjdaghfKJSDHjhdsgf/JKSHF/FD/SsfkhafdAJkoijewfkldjfoqwenfaWs
  LKJFHkdjhgKHSDsdklgjhafgLKLSFHasgiohKFaewg902135JKABDfjkwaeg
  KDJGHO98q3745hKFJEFiwege/wegq/f2e4qgjfaoi89237rHUGFJHWFf782g
  LKJKJEHFwelqfkhilqweheflqwefiuqwyry8rJKAFG==]
```
