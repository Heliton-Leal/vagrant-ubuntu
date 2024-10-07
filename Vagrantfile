
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "public_network", bridge: "eth1"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "Projeto_01 - Primeira VM"
    vb.cpus = 2
    vb.memory = "2048"
  end
end
