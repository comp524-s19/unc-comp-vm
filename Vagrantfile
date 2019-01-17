# vi: set ft=ruby :
Vagrant.configure(2) do |config|  
  config.vm.define "comp524-s19" do |box|
    box.vm.network "private_network", ip: "33.33.33.33"
    box.vm.box = "pozefsky/comp524-s19"
    box.vm.provider "virtualbox" do |v|
     v.name = "UNC COMP 524 VM"
     v.gui = false
     v.memory = 1024
     v.cpus = 2
    end
  end
end
