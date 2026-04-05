Vagrant.configure("2") do |config|  # <--- THIS MUST BE LINE 1

  config.vm.define "server" do |server|
    server.vm.box = "ubuntu/jammy64"
    server.vm.network "private_network", ip: "192.168.56.10"
    
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "setup_web.yml"
    end
  end

  config.vm.define "client" do |client|
    client.vm.box = "debian/bookworm64"
    client.vm.network "private_network", ip: "192.168.56.11"
  end

end # <--- THIS MUST BE THE VERY LAST LINE
