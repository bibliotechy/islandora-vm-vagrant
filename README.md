islandora-vm-vagrant
====================

A really simple wrapper around the 1.4 release of the [Islandora Virtual Machine Image](http://islandora.ca/downloads) which is a complete build of the [Islandora Chef](https://github.com/ryersonlibrary/islandora_chef) repo.


## Requirements
  [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  
  [Vagrant](https://docs.vagrantup.com/v2/installation/index.html)

**I've only tested on linux and OSX**

##Getting Started

`git clone https://github.com/bibliotechy/islandora-vm-vagrant.git`

`cd islandora-vm-vagrant`

`vagrant up`

Now go make a cup of coffee, or tea, or some other kind of beverage, because the first time you run this, it has to download a huge file. 

When it is done, your new islandora instance will be available. 

Point your favorite browser at `[http://localhost:8181](http://localhost:8181).

 To login to the virtual machine, just
 
`vagrant ssh`  

while inside the `islandora-vm-vagrant` directory
