## Executing r10k to Deploy Your Environments

```
# The r10k deploy subcommand

NAME
    deploy - Puppet dynamic environment deployment

USAGE
    r10k deploy <subcommand>

DESCRIPTION
    `r10k deploy` implements the Git branch to Puppet environment workflow
    (https://puppetlabs.com/blog/git-workflow-and-puppet-environments/).

SUBCOMMANDS
    display         Display environments and modules in the deployment
    environment     Deploy environments and their dependent modules
    module          Deploy modules in all environments

OPTIONS
       --cachedir    Specify a cachedir, overriding the value in config

OPTIONS FOR R10K
    -c --config      Specify a global configuration file
       --color       Enable colored log messages
    -h --help        Show help for this command
    -t --trace       Display stack traces on application crash
    -v --verbose     Set log verbosity. Valid values: fatal, error, warn, notice, info, debug, debug1, debug2
```
