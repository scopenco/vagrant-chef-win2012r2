# Vagrant Windows 2012r2 Environment with Chef provisiover

### Desciprion

This Vagrant Environment deploy Windows 2012r2 VM for local development.

### Requirments

* [Parallels Desktop for Mac Pro Edition](http://www.parallels.com/products/desktop/download/) or VirtualBox
* [Vagrant](https://www.vagrantup.com/downloads.html) 1.7.0 or higher
* Vagrant plugins: `vagrant-parallels`, `vagrant-berkshelf`, `vagrant-winrm`

### Usage
1. Clone git repository and run ```vagrant up```
2. Login to VM, wait until Parallels Tools setup will be done
3. Poweroff VM, and run ```vagrant up``` again

### Authors

* Author:: Andrei Skopenko (andrei@skopenko.net)
