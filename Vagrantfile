Vagrant.configure(2) do | config |
  config.vm.box = "https://cloud-images.ubuntu.com/xenial/current/xenial-server-cloudimg-amd64-vagrant.box"
  config.vm.provision :shell, :path => "./init.sh",:privileged   => true
end
