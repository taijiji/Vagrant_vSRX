# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "juniper/ffp-12.1X47-D15.4-packetmode"
  config.vm.network "private_network", ip: "192.168.33.3", netmask: "255.255.255.0"
  config.vm.network "private_network", ip: "192.168.33.4", netmask: "255.255.255.0"
end
