# My-DevOps-environnement
This repository contains notes and files to help you build your devops environnement on Centos7 
## Requirements 
### Installation of VirtualBox on centos 7 

#### Step 1: Download VirtualBox Repository
  1. https://www.virtualbox.org/wiki/Linux_Downloads By clicking on the third option Oracle Linux 7 / Red Hat Enterprise Linux 7 / CentOS 7 ,
	   the download will be initiated right away.
  2. Or run this command:
      > sudo wget http://download.virtualbox.org/virtualbox/rpm/el/virtualbox.repo -P /etc/yum.repos.d
      
      
#### Step 2: Install VirtualBox 7.0

  1.   Run this command: 
         > sudo yum install VirtualBox-7.0-7.0.4_154605_el7-1.x86_64.rpm
  2. Intallation of VirtualBox 7.0.4 Oracle VM VirtualBox Extension Pack
      Go back to the previous site https://www.virtualbox.org/wiki/Downloads 
      And by clicking on "All supported platforms" , as shown above, the download will be initiated.
  3. Run the command:
        > sudo VBoxManage extpack install Oracle_VM_VirtualBox_Extension_Pack-7.0.4.vbox-extpack
  4. To open virtualBox, tun the command: 
        > VirtualBox 


