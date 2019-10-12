
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

2.sudo apt-get install golang-go <br />

#Setup Go Path <br />

3.export GOPATH=$HOME/go <br />

4.export PATH=$PATH:$GOPATH/bin <br />

#### Install Docker for Ubuntu

 **Docker-ce** - Base package which makes all the necessary files available for the docker container to run properly. <br />
 
 **Docker-compose**- Base package which makes all the necessary files available for the docker container to run properly. <br />
 

5.curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - <br />

 
6.sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

 
7.sudo apt-get update

 
8.apt-cache policy docker-ce

  
9.sudo apt-get install -y docker

 
10.sudo apt-get install docker-compose

 
11.sudo systemctl status docker
  
  
#Check Docker Version

12.docker-compose --version

#Running Docker Daemon

13.dockerd





