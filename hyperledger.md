
Hyperledger 
========

---
**NOTE**

 "Hyperledger is an open sourced community of communities to benefit an ecosystem of Hyperledger based solution providers and users focused on blockchain related use cases that will work across a variety of industrial sectors.
  – Brian Behlendorf, Executive Director of Hyperledger." 
 
---

## Hyperledger Setup

#### install Curl

1.sudo apt-get install curl

#### install go language

sudo apt-get install golang-go

2.# Setup Go Path 

3.export GOPATH=$HOME/go

4.export PATH=$PATH:$GOPATH/bin

#### Install Docker for Ubuntu

 **Docker-ce** - Base package which makes all the necessary files available for the docker container to run properly. 
 
 **Docker-compose**- Base package which makes all the necessary files available for the docker container to run properly.
 
--- 

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

 
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

 
sudo apt-get update

 
apt-cache policy docker-ce

  
sudo apt-get install -y docker

 
sudo apt-get install docker-compose

 
sudo systemctl status docker
  
  
#Check Docker Version

docker-compose --version

#Running Docker Daemon

dockerd

---



