# vi: set ft=ruby :

Vagrant.require_version ">= 1.6.3"

Vagrant.configure(2) do |config|
  config.vm.box = "trusty64"
  config.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box"
  config.vm.network "private_network", ip: "192.168.100.2"
end
