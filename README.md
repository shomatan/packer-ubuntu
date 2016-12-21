# packer-ubuntu
Packer templates to build the vagrant box for Ubuntu.

## Requirements
+ [Packer](https://www.packer.io/)
+ [VirtualBox](https://www.virtualbox.org/)

## Usage
#### Ubuntu 16.04
```
packer build latest.json
vagrant box add ubuntu-16.04 builds/virtualbox-ubuntu-16.04.box
```
