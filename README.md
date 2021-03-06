# GFW JSON Service

[![Build Status](https://travis-ci.org/gfw-api/gfw-json-adapter.svg?branch=master)](https://travis-ci.org/gfw-api/gfw-json-adapter) [![Code Climate](https://codeclimate.com/repos/572a17190f49f713e5000eba/badges/a3859d6ec83d646055ab/gpa.svg)](https://codeclimate.com/repos/572a17190f49f713e5000eba/feed) [![Test Coverage](https://codeclimate.com/repos/572a17190f49f713e5000eba/badges/a3859d6ec83d646055ab/coverage.svg)](https://codeclimate.com/repos/572a17190f49f713e5000eba/coverage)

TODO: Write a project description

## Installation

Requirements:

* Ruby 2.3.0 [How to install](https://gorails.com/setup/osx/10.10-yosemite)
* PostgreSQL 9.4+ [How to install](http://exponential.io/blog/2015/02/21/install-postgresql-on-mac-os-x-via-brew/)

Install global dependencies:

    gem install bundler

Install project dependencies:

    bundle install

## Usage

First time execute:

    cp config/database.yml.sample config/database.yml

    bundle exec rake db:create
    bundle exec rake db:migrate

To run application:

    bundle exec rails server

## TEST

  Run rspec:

    bin/rspec

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request :D

### BEFORE CREATING A PULL REQUEST

  Please check all of [these points](https://github.com/gfw-api/gfw-json-adapter/blob/master/CONTRIBUTING.md).
