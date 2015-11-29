# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"


Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
# use the same key for each machine
config.ssh.insert_key = false

  config.vm.define "web00" do |web00|
    web00.vm.box = "ubuntu/trusty64"
    web00.vm.hostname = "web00"
  end

  config.vm.define "web01" do |web01|
    web01.vm.box = "ubuntu/trusty64"
    web01.vm.hostname = "web01"
  end

  config.vm.define "web02" do |web02|
    web02.vm.box = "ubuntu/trusty64"
    web02.vm.hostname = "web02"
  end
end
