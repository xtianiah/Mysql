# Mysql
#### Mysql was downloaded in ubuntu following the neccesary steps
#### I used ls to list the files making sure the filename is listed as mysql-apt-config_0.8.10-1 _all.deb
#### Mysql was then installed using sudo dpkg -i mysql-apt-config* in order to add repositories
####  I refreshed the apt package cache to making sure the new software package was availabe using sudo apt update
#### Sudo apt install mysql-server was used to install the latest MySql server package
#### I used sudo systemctl status mysql to check the activeness of Mysql
#### The status of Mysql was tested using mysqladmin -u root -p version
#### Mysql is successfully installed and running.
