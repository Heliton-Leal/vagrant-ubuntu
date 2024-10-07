
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.network "public_network", bridge: "eth1"
  config.vm.synced_folder "./pasta_local", "/curso"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "Projeto_01 - Primeira VM"
    vb.cpus = 1
    vb.memory = "1024"
  end
end
