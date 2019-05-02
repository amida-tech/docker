# Setting up Docker on Mac OS X

**DEPRECATED: Officially supported, see: https://docs.docker.com/docker-for-mac/**

_(loosely based on (http://johnzanchetta.wordpress.com/2014/02/08/setting-up-a-docker-dev-environment-on-mac-os-x/)[this])_

## Prerequisites

* Mac OS X
* homebrew
* docker client
* Vagrant
* VirtualBox
* Centos 7 box

## Usage

```
#install docker client
brew install docker

#check client is installed
docker version

#initialize Vagrant box using Centos 7.0
vagrant init chef/centos-7.0

#launch box (will download Centos 7.0 box)
vagrant up

#check your boxes
vagrant box list
```
