# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "kalilinux/rolling"
  config.vm.provision "ansible_local" do |a|
    a.playbook = "playbook.yml"
  end
end
