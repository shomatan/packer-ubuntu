Vagrant.configure("2") do |config|

  if Vagrant.has_plugin?("vagrant-cachier")
      config.cache.scope = :box
  end

  config.ssh.insert_key = false
  config.vm.box = "ubuntu-16.04"
  config.vm.box_url = "file://builds/virtualbox-ubuntu16.04.box"

  config.vm.define :default do |machine|
    machine.vm.hostname = "default"
    machine.vm.network :private_network, ip: "192.168.33.10"
  end

end
