# General-danted-proxy

this bash file is for google VM only cuz the google vm ifconfig is ens4

## remember to run this before bash file 
sudo chmod +x run.sh

## add user
sudo useradd -M -s /usr/sbin/nologin -p $(openssl passwd -1 {PASSWORD}) {USER}
