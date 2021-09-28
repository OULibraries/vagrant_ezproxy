Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"



  # Disable generation of new key, fall back on vagrant default key. 
  config.ssh.insert_key = false

  # config.vm.provision "ansible" do |ansible|
  #   ansible.verbose = "v"
  #   ansible.playbook = "ezproxy_provision.yml"
  # end
end

