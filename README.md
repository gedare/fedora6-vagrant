# fedora6-vagrant

Get Started
-----------

1. Install virtualbox.

2. Install vagrant, if you have not already. Prefer to use the latest version from http://www.vagrantup.com/downloads. The virtual machine was created and tested with version 1.8.1.

3. Run `$ vagrant up`

4. Run `$ vagrant ssh`. Read Vagrant documentation for more commands.

5. Hack.

Notes
-----
* sudo can be run without a password by the vagrant user.
* Login credentials:
** username/password: vagrant/vagrant
** root password: vagrant
* The guest and host share a directory. In the VM it is /vagrant, and in the host it is the directory from which you run `vagrant up`.