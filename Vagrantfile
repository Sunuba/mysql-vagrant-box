# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network :forwarded_port, guest: 3306, host: 3306
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.provider "virtualbox" do |vb|
    # change this according to your needs.
    vb.memory = 512
    # change this accoring to your needs.
    vb.cpus = 1
  end
  config.vm.provision :shell, :path => "install.sh"
end
