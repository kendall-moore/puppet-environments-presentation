## An Example Puppetfile

```ruby
Install zack/r10k and keep it up to date with 'master'
mod 'zack/r10k', :latest

# Install puppetlabs/apache and track the 'docs_experiment' branch
mod 'puppetlabs/apache',
  :git => 'https://github.com/puppetlabs/puppetlabs-apache',
  :ref => 'docs_experiment'

# Install puppetlabs/ntp and pin to the '2.0.0' tag
mod 'puppetlabs/ntp',
  :git => 'https://github.com/puppetlabs/puppetlabs-ntp',
  :tag => '2.0.0'

# Install puppetlabs/apache and pin to the '4d8cb3b' commit
mod 'ghoneycutt/dnsclient',
  :git    => 'https://github.com/ghoneycutt/puppet-module-dnsclient',
  :commit => '4d8cb3b29e321eed6c446d4cd1948dfbd4e0a506'
```
