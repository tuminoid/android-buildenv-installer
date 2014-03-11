# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :androidenv do |config|
    # Vagrant 1.5 type naming
    config.vm.box = "hashicorp/precise64"
    
    config.vm.provision :shell, :path => "install.sh"
  end
end
