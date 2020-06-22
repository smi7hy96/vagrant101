# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # Our python ebooks will run here because it will be similar to the test
  config.vm.box = "ubuntu/xenial64"
  # refer to .sh file to always install nginx on vagrant up
  config.vm.provision "shell", path: "provision.sh"
  # the reverse proxy will give man an entry into my run machine
  config.vm.network("private_network", ip: "192.168.10.100")
  # Asking developers to go to an ip is not user friendly
  # lets give them a host with letters for them to access and view their amazing dev work

  # you need to install a vagrant plugin
  # vagrant plugin install vagrant-hostupdater
  # development.local
  config.hostsupdater.aliases = ["developmentiscool.local"]
end
