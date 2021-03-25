
Vagrant.configure("2") do |config|

  config.vm.define "master" do |master|
    master.vm.box = "centos/8"
    master.vm.network "private_network", ip: "192.168.3.100"
    master.vm.hostname = "master"
    master.vm.provision "ansible" do |ansible|
    ansible.playbook = "master.yml"
    end
  end

  config.vm.define "node1" do |node1|
    node1.vm.box = "centos/8"
    node1.vm.network "private_network", ip: "192.168.3.101"
    node1.vm.hostname = "node1"
    node1.vm.provision "ansible" do |ansible|
      ansible.playbook = "node.yml"
    end
  end

  config.vm.define "node2" do |node2|
    node2.vm.box = "centos/8"
    node2.vm.network "private_network", ip: "192.168.3.102"
    node2.vm.hostname = "node2"
    node2.vm.provision "ansible" do |ansible|
      ansible.playbook = "node.yml"
    end
  end
  config.vm.define "node3" do |node3|
    node3.vm.box = "centos/8"
    node3.vm.network "private_network", ip: "192.168.3.103"
    node3.vm.hostname = "node3"
    node3.vm.provision "ansible" do |ansible|
      ansible.playbook = "node.yml"
    end
  end
  config.vm.define "node4" do |node4|
    node4.vm.box = "centos/8"
    node4.vm.network "private_network", ip: "192.168.3.104"
    node4.vm.hostname = "node4"
    node4.vm.provision "ansible" do |ansible|
      ansible.playbook = "node.yml"
    end
  end
end
