Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  
  config.vm.define "GB_HP" do |t|
  end

  config.vm.provider "virtualbox" do |v|
    v.name = "GB_HP"
  end


  config.vm.network "private_network", ip: "192.168.2.10"
    config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
  end

end
