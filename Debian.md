## 1. Switch to testing repos
cd /etc/apt/
sudo cp sources.list sources.list.backup

deb http://ftp.us.debian.org/debian/ sid main
deb-src http://ftp.us.debian.org/debian/ sid main

sudo apt update
sudo apt upgrade

sudo apt-get update 
sudo apt-get dist-upgrade 
sudo apt-get autoremove 
sudo reboot

