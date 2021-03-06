## Sensu-Plugins-twemproxy

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-twemproxy.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-twemproxy)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-twemproxy.svg)](http://badge.fury.io/rb/sensu-plugins-twemproxy)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-twemproxy/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-twemproxy)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-twemproxy/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-twemproxy)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-twemproxy.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-twemproxy)

## Functionality

## Files
 * bin/metrics-twemproxy

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-twemproxy -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-twemproxy`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-twemproxy' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-twemproxy' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
