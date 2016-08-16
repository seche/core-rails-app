# core-rails-app
Just a basic app including specific gems as a starting point.

# MySQL
Root User: seche
Database Name: c9

## start MySQL
$ mysql-ctl start

## stop MySQL
$ mysql-ctl stop

## run the MySQL interactive shell
$ mysql-ctl cli

## Connecting
$servername = getenv('IP');
$username = getenv('C9_USER');
$password = "";
$database = "c9";
$dbport = 3306;

Hostname - $IP (The same local IP as the application you run on Cloud9)
Port - 3306 (The default MySQL port number)
User - $C9_USER (Your Cloud9 user name)
Password - "" (No password since you can only access the DB from within the workspace)
Database - c9 (The database username)

https://community.c9.io/t/setting-up-mysql/1718

# Postgresql

https://community.c9.io/t/setting-up-postgresql/1573
User: ubuntu
Password: h=xwyV-PEPXsP7rd



rails s -b $IP -p $PORT