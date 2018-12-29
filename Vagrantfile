# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.synced_folder "../k8s-up", "/k8s-up"
  config.vm.network "public_network",use_dhcp_assigned_default_route:true
  config.vm.define "master0" do |master0|
    master0.vm.box = "ubuntu1604"
    master0.vm.hostname = "master0.chief"
  end
  config.vm.define "node0" do |node0|
    node0.vm.box = "ubuntu1604"
    node0.vm.hostname = "node0.swarm"
  end
  config.vm.define "node1" do |node1|
    node1.vm.box = "ubuntu1604"
    node1.vm.hostname = "node1.swarm"
  end
  config.vm.define "node2" do |node2|
    node2.vm.box = "ubuntu1604"
    node2.vm.hostname = "node2.swarm"
  end
  config.vm.define "node3" do |node3|
    node3.vm.box = "ubuntu1604"
    node3.vm.hostname = "node3.swarm"
  end

end
