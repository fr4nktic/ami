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
* Ruby 1.9.3 stable
* [Homebrew](https://github.com/mxcl/homebrew) (Package management for OS X)
* Wget (Download stuff from the internet)
* Git (Version control of awesomeness)
* Ack (A tool for searching within files)
* Redis (A key-value data store)
* ImageMagick (An image manipulation library)
* Nginx (The web server that can)

### Gems

* Bundler
* Rails
* Heroku
* Taps (push and pull SQL databases between environments)

### RDBMS _(optional)_

* SQLite and the sqlite gem
* PostgreSQL and the pg gem
* MySQL and the mysql2 gem

## Updating

### Homebrew

* `brew update` updates formulae and Homebrew itself
* `brew upgrade [formula]` installs newer version of `formula`
* `brew upgrade` installs newer versions of outdated packages


### ruby-build

    cd ~/ruby-build
    git pull
    sudo ./install.sh

### rbenv

    cd ~/.rbenv
    git pull

