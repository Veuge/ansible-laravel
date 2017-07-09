Vagrant.configure("2") do |config|

    config.vm.define :web do |web_config|
        web_config.vm.box = "debian/jessie64"
        web_config.vm.network :private_network, ip: "192.168.1.5"
    end
end
