#Create new project: (Base Box)

    vagrant init precise64 http://files.vagrantup.com/precise64.box

#Manage vagrant boxes

    vagrant box

#Add a new box and if existing override

    vagrant box add precise64 http://files.vagrantup.com/precise64.box --force
    
#List boxes

    vagrant box list

#Vagrant start box

    vagrant up

#Vagrant suspend box

    vagrant Suspend

#Vagrant resume box

    vagrant resume

#Vagrant stop box

    vagrant halt

#Vagrant destroy the box instance

    vagrant destroy

#Connect to the vagrant box through ssh

    vagrant ssh

#List all the instances of vagrant boxes on the system

    Vagrant global-status

#Destroy vagrant box by ID

    Vagrant destroy 123124

    config.vm.network :forwarded_port, guest: 8080, host: 8888
