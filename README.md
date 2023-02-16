# DevOps-PBL-project-1
Devops PROJECT 1: LAMP STACK IMPLEMENTATION

## update a list of packages in package manager
sudo apt update
![server update](./images/server-update.png)

## run apache2 package installation
sudo apt install apache2
![install apache2](./images/install-apache.png)

## To verify that apache2 is running as a Service in our OS, use following command
sudo systemctl status apache2
![check apache status](./images/apache-status.png)

## Installing mysql
sudo apt install mysql-server
![install mysql](./images/install-mysql.png)

## Assignin password to mysql root user account
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';
![adding mysql password](./images/sudo-mysql2.png)

## validating root user password
sudo mysql_secure_installation
![validating mysql password](./images/mysql-password-validation.png)

## Install php and its dependencies
![installing php](./images/install-php.png)


## configure apache2 server and enable new site configuration
![configuring apache cong file](./images/configure-apache.png)
