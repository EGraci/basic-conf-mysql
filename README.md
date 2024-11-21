# basic-conf-mysql
## login mysql
```mysql -u usrename -p```
## create databes
```CREATE DATABASE nameDatabase;```
## create user
```CREATE USER 'user'@'localhost' IDENTIFIED BY 'password'```
## configurate access
```GRANT ALL PRIVILEGES ON `nameDatabase`.* TO 'user'@'localhost';```
## remove grant option
```REVOKE GRANT OPTION ON `nameDatabase`.* FROM 'user'@'localhost'```
