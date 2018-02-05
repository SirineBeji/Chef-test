Vagrant.configure("2") do |config|
  config.vm.define "workstation" do |w|
    w.vm.box = "ubuntu/trusty64"
    w.vm.network "private_network", ip:"192.168.0.252"
    w.vm.hostname  = "workstation"
  end
end
