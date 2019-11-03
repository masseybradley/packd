Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.box_version = "20191030.0.0"
  config.ssh.insert_key = false
  config.vm.provider "virtualbox" do |vb|
     vb.gui = false
     vb.memory = "4192"
     vb.cpus = 4
  end
end

