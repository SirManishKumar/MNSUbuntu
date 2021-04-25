# MNSUbuntu
This is a script that allows you to install Ubuntu in your termux application without a rooted device.

Updates
• Updated to ubuntu 20.04+

Installation steps
Update termux: apt-get update && apt-get upgrade -y
Install wget: apt-get install wget -y
Install proot: apt-get install proot -y
Install git: apt-get install git -y
Go to HOME folder: cd ~
Download script: git clone https://github.com/SirManishKumar/MNSUbuntu
Go to script folder: cd MNSUbuntu
Give execution permission: chmod +x ubuntu.sh
Run the script: ./ubuntu.sh -y
Now just start ubuntu: ./startubuntu.sh
