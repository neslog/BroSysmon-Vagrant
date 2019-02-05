Vagrant.configure("2") do |config|
  config.vm.box = "neslog/ZeekReady"
  config.vm.box_version = "0.1"
  config.ssh.private_key_path = ["~/vagrant_ecdsa","keys/vagrant_ecdsa"]
  config.vm.network "private_network", ip: "192.168.100.1", virtualbox__intnet: true 
end
