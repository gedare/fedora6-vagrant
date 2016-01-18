# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "mgazanayi/fedora-6-i386"
  config.vm.box_url = "https://atlas.hashicorp.com/mgazanayi/boxes/fedora-6-i386"

  config.vm.network "private_network",  type: "dhcp"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "fedora6"
    vb.cpus = 1
    vb.customize ["modifyvm", :id, "--memory", "1024"]
  end

end
