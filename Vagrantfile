Vagrant.configure("2") do |config|
  # Перша віртуальна машина: Ubuntu 18.04
  config.vm.define "vm1" do |vm1|
    vm1.vm.box = "hashicorp/bionic64"
    vm1.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.cpus = 1
    end
  end

  # Друга віртуальна машина: Debian 11
  config.vm.define "vm2" do |vm2|
    vm2.vm.box = "debian/bullseye64"
    vm2.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end
end