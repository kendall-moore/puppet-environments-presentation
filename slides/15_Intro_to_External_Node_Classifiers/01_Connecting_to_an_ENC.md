## Connecting to an ENC

* There are two variables that must be set in puppet.conf in order to connect to an ENC

```
[master]
  # Tell the master that we are using an ENC
  node_terminus = exec

  # Tell the master where the executable to connect is
  external_nodes = /usr/local/bin/puppet_node_classifier
```
