## Configuring and Enabling Environments

```ruby
# Puppet.conf on the master node(s).
[main]
  # Lists directories of global modules that all environments can access by default.
  basemodulepath = /etc/puppet/modules:/opt/puppet/share/puppet/modules

  # Is the list of directories where Puppet will look for environments.
  environmentpath = /etc/puppet/environments

  # specifies the main manifest for any environment that doesn’t set a manifest value in environment.conf.
  default_manifest = /etc/puppet/manifests/site.pp

  # Lets you specify that all environments should use a shared main manifest. This requires default_manifest to be set to an absolute path.
  disable_per_environment_manifest = false

  # Sets how often the Puppet will refresh information about environments. 
  environment_timeout = 0
```

