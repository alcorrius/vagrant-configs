# Vagrant-configs
Configs for vagrant

## Instructions
###1. Install Vagrant and VirtualBox:
  - sudo apt-get install virtualbox
  - sudo apt-get install vagrant

###2. Initialize Vagrant in PHPStorm project:
  PHPStorm->Tools->Vagrant->Init in Project Root

###3. Replace content of Vagrantfile by downloaded config file

###4. Set config parameters:
  - Change IP address
  - Configure synced folders
  - Download Oracle libraries and put them into the synced folder
  - Create apache virtualhost config file and put it into the synced folder

###5. Start virtual machine:
  PHPStorm->Tools->Vagrant->Up
  
###6. Check for errors in PHPStorm command line. If needed start ssh session in PHPStorm and manually fix problems.
