
# Download IE VM images from https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/
# # and unzip them into a folder.
# This Vagrant file works after running a command like
# # vagrant box add ~/dw/IE10.Win7.Vagrant/IE10\ -\ Win7.box --name microsoft-VAGRANTSLASH-IE10-Win7-20170112a

Vagrant.configure("2") do |c|
  Vagrant.require_version ">= 1.8.1"
  c.ssh.insert_key = false
  c.vm.define 'ie10-win7.ms' do |v|
    v.vm.hostname = 'ie10-win7.ms'
    v.vm.box = 'microsoft/IE10-Win7-20170112a'
  end
end

#
