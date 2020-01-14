
# AnsibleRoleForLocalhostSetup
An Ansible role for setting up my localhost
# About
This is an Ansible role to setup my localhost.
 - The installed packages will be updated to the latest version
 
The following software will be removed:
- gnome-mahjongg
- gnome-mines
- gnome-sudoku
- gnome-boxes
- virt-manager

The following packages will be installed:
- git
- nautilus
- gnome-terminal
- net-tools
- curl
- wget
- snapd
- python3
- python3-pip
- python3-tk
- nano
- vim
- apache2

The following apps will be installed:
 - Google Chrome
 - VisualStudio Code
 - Oracle VirtualBox

The following configs will also be done:
 - Ubuntu's multiverse repos
 - Install Vundle and configure .vimrc accordingly
 - SSH keys are copied to ~/.ssh (temp keys are in the files dir)
