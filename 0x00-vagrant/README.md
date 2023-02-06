# How to Install Vagrant for Windows
While I will give a brief summary of how to install vagrant, it is always best to read the [documentation](https://developer.hashicorp.com/vagrant/docs) yourself. 

1. Download and install [virtual box](https://www.virtualbox.org/wiki/Downloads)
2. Download and install [vagrant](https://developer.hashicorp.com/vagrant/downloads)
3. Open your command prompt
4. Add the **Ubuntu 20.04 (Focal) image** to your box list
```
vagrant box add ubuntu/focal64
```
5. Create your virtual machine
```
vagrant init ubuntu/focal64
```
6. To avoid issues with the last version of Vagrant (2.2.4 or latest) run the following command
```
vagrant plugin install vagrant-vbguest
```
7. Start your virtual machine
```
$ vagrant up
```
8. Enter your virtual machine
```
$ vagrant ssh
```

