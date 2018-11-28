 ## Working with this repository

1. Clone it using git

2. Install [Vagrant](https://www.vagrantup.com/downloads.html)

3. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## Provision Vagrant

1. `cd trellis`

2. `vagrant up`

## Access
1. Now you can go to https://roots-example-project.test/wp/wp-admin/ (creds admin, admin), configure and install latest wordpress-static-html-plugin to test it.

2. You SSH into the VM machine by running `vagrant ssh`

3. Files will be under the local folder `/site`. Wordpress will be installed as part of `vagrant up` provisioning.
