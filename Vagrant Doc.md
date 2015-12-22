# Vagrant Doc - Romain



##### Vagrant Operations

`Vagrant init` : load a VM for the first time (will copy locally)

`Vagrant up` : Execute the VM (a.k.a perform the installation if necessary then create an ssh user)

`Vagrant ssh` : get into the VM with the SSH user

`Vagrant halt` : stop the VM 

##### MySQL

`mysql -h localhost -u root -prootpass DB_Prod<dump.sql` : Import the dump

`pv ./Shared/dump.sql | mysql -u root -prootpass -h localhost DB_Prod` : import the dump and see how it advances 

`show database`

`drop database`

`create table`

`drop table`

##### Python

`pip list` : display the list of the python packages

`sudo conda install mysql-connector-python`

