## Sensu-Plugins-percona

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-percona.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-percona)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-percona.svg)](http://badge.fury.io/rb/sensu-plugins-percona)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-percona/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-percona)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-percona/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-percona)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-percona.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-percona)

## Functionality

## Files
 * bin/check-percona-cluster-size
 * bin/metrics-percona-cluster

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-percona -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-percona`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-percona' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-percona' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
