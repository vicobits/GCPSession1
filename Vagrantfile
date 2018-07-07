# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/xenial64"

  config.vm.hostname = "GCPSession1"
  config.vm.box_check_update = true

  config.vm.network "private_network", ip: "192.168.33.190"
  config.vm.synced_folder "./", "/code", disabled: false

  config.vm.provider "virtualbox" do |vb|
     vb.gui = false
     vb.memory = "1024"
     vb.name = "GCPSession1"
  end

end
