# mysql-vagrant-box
mysql vagrant box on Ubuntu 16.04 (xenial)

## Installation
clone the repository and run vagrant up.  
It will create an Ubuntu 16.04 64-bit and install mysql latest version.

## How to connect?
Host: 192.168.33.10  
Port: 3306  
username: root  
password: root  

You can set your own username and password inside <b>install.sh</b> file.  
You can also change host, port, username and password inside <b>Vagrantfile</b>

## PHPMyAdmin
Additionall, it will install PHPMyAdmin and it is accessible from 192.168.33.10/phpmyadmin  
username and password is: root
