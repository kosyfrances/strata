# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"

  config.vm.define "auth" do |auth|
    auth.vm.hostname = "auth"
    auth.vm.network "private_network", ip: "192.168.34.10"

    auth.vm.provider "virtual box" do |vb|
      vb.memory = 1024
      vb.cpus = 1
    end
  end

end
