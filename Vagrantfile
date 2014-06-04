# -*- mode: ruby -*_
# vi: set ft=ruby ;

Vagrant.configure('2') do |config|
  config.vm.hostname = 'dynamic-motd'
  config.vm.box = 'boxes-wheezy64-chef'
  config.vm.box_url = 'http://boxes.nickcharlton.net/wheezy64-chef-vmware.box'

  config.vm.provision 'shell', inline: 'sudo apt-get -yqq install figlet' 
end
