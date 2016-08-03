Vagrant::Config.run do |config|
  config.vm.box="ubuntu/trusty64"
  config.vm.forward_port 80, 3000

  # Using Puppet
  config.vm.provision :puppet
end
