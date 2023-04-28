Vagrant.configure("2") do |config| 
  config.vm.box = "centos/7"  
  config.vm.hostname = "prometheus"
  config.vm.network "private_network", ip: "192.168.56.7"
  config.vm.provision "shell", path: "provision.sh"
  config.vm.provider 'virtualbox' do |v|
    v.memory = 1024
  end
end
