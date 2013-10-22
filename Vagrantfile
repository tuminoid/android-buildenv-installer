# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :precise64 do |precise64|
    precise64.vm.box = "precise64"
    precise64.vm.box_url = "http://files.vagrantup.com/precise64.box"
    precise64.vm.provision :shell, :path => "install.sh"
  end
end
