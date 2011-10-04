# AMI

AMI (_pronounced Amy /ey-mee/_) is the **A**wesome **M**ac **I**nstaller that sets up a Rails development environment on a Mac.

## Installation

Before using AMI make sure you have [Git](http://git-scm.com/) and [GCC for OS X](https://github.com/kennethreitz/osx-gcc-installer) (_OS X 10.6 or higher required_). No Xcode needed.

Then run this one-liner:

    bash <(curl -s https://raw.github.com/frankzilla/ami/master/install)

## What does AMI do?

AMI configures and installs the following libraries:

* Generate your SSH public keys _(optional)_
* [rbenv](https://github.com/sstephenson/rbenv) and [ruby-build](https://github.com/sstephenson/ruby-build) (Simple Ruby version management)
* Ruby 1.9.2 stable
* [Homebrew](https://github.com/mxcl/homebrew) (Package management for OS X)
* Ack (A tool for searching within files)
* Redis (A key-value data store)
* ImageMagick (An image manipulation library)
* [Janus](https://github.com/carlhuda/janus) (A Vim distribution - _optional_)

###Gems

* Bundler
* Rails
* Heroku
* Taps (push and pull SQL databases between environments)

###RDBMS _(optional)_

* PostgreSQL and the pg gem
* MySQL and the mysql2 gem
