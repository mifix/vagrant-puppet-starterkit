Vagrant - Puppet Starterkit
===========================

Starterkit for creating VMs with vagrant and Puppet.

This kit provides a minimal ``Vagrantfile`` to start a Ubuntu Server 12.04 VM with puppet preinstalled.

Puppet and [librarian-puppet](https://github.com/rodjek/librarian-puppet) ist installed via rubygems.


##  Prerequisites

  * Vagrant
  * Virtualbox
  * bundler (``gem install bundler``)


##  Howto use

  * clone the repo
  * $ bundle install
  * edit Puppetfile
  * $ bundle exec librarian-puppet install
  * edit Vagrantfile (optional)
  * $ vagrant up
