#

### Dockerized Django

Django 3.7.4

# How to Install Docker 
## Ubuntu
``` sh
$ sudo apt-get update

$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

$ sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
```
## Windows
See [Docker For Windows](https://docs.docker.com/docker-for-windows/install/)

#### Images
```sh 
// To see list of Images
docker image ls

// Delete Image by ID 
docker image rm <ID>
```
