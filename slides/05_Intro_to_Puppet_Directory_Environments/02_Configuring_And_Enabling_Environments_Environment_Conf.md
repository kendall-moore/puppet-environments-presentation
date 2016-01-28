## Configuring and Enabling Environments

```ruby
# Sample environment.conf for a Puppet directory environment

# Module directories for this specific environment
modulepath = modules:site:$basemodulepath

# A helper script to specify the Git version of this environment (Spoiler alert!)
config_version  = 'scripts/config_version.sh $environmentpath $environment'

```
