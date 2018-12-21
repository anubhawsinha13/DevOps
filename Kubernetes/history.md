 vagrant
    2  apt install vagrant
    3  sudo apt install vagrant
    4  vagrant
    5  ansible
    6  sudo apt install ansible
    7  ls
    8  pwd
    9  mkdir kubernetes
   10  cd kubernetes/
   11  touch vagrantfile
   12  vi vagrantfile
   13  vagrant up
   14  vi vagrantfile
   15  vagrant up
   16  vi vagrantfile
   17  vagrant up
   18  cd ../
   19  ls
   20  vagrant up --provider virtualbox
   21  cd kubernetes/
   22  vagrant up --provider virtualbox
   23  sudo apt-get update && sudo apt-get dist-upgrade && sudo apt-get autoremove
   24  udo apt-get -y install gcc make linux-headers-$(uname -r) dkms
   25  sudo apt-get -y install gcc make linux-headers-$(uname -r) dkms
   26  ls
   27  cd ../
   28  ls
   29  mkdir VirtualBox
   30  cd VirtualBox/
   31  wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
   32  wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -
   33  wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
   34  sudo sh -c 'echo "deb http://download.virtualbox.org/virtualbox/debian $(lsb_release -sc) contrib" >> /etc/apt/sources.list'
   35  sudo apt-get update
   36  udo apt-get install virtualbox-5.2
   37  sudo apt-get install virtualbox-5.2
   38  VBoxManage -v
   39  curl -O http://download.virtualbox.org/virtualbox/5.2.0/Oracle_VM_VirtualBox_Extension_Pack-5.2.0-118431.vbox-extpack
   40  sudo VBoxManage extpack install Oracle_VM_VirtualBox_Extension_Pack-5.2.0-118431.vbox-extpack
   41  VBoxManage list extpacks
   42  cd ../
   43  ls
   44  cd kubernetes/
   45  ls
   46  vagrant up
