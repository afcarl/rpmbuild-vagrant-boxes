# rpmbuild-vagrant-boxes

[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](http://www.repostatus.org/badges/latest/inactive.svg)](http://www.repostatus.org/#inactive)

A collection of Vagrantfiles for boxes to build RPMs

These boxes should have the minimum dependencies to build RPMs installed on them. They use the official [PuppetLabs Vagrant boxes](https://vagrantcloud.com/puppetlabs),
and have Puppet installed for convenience.

If you want to install EPEL, just ``sudo yum install epel-release``.
