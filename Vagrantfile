# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "neo4j"
  config.vm.box_url = "http://s3.amazonaws.com/sandbender-boxes/sprockets_account_database_virtualbox.box"
  config.vm.network :forwarded_port, guest: 7474, host: 7474
end
