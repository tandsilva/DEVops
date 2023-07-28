
Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"

  config.vm.provider "virtualbox" do |vb|
  
  end

  config.vm.network "forwarded_port", guest: 80, host: 8083, host_ip: "127.0.0.1"

  config.vm.provision "shell", path: "provision.sh"

end