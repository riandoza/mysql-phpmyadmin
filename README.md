# Run MySQL and phpMyAdmin with Docker Compose

Usage :
> docker-compose up -d

All data saving at folder **data/**

## Access MySQL command

as root
> mysql --host=127.0.0.1 --port=3307 -u root -p
> mysql> SHOW DATABASES;

or as a user
> mysql --host=127.0.0.1 --port=3307 -u testuser -p
> mysql> SHOW DATABASES;

## Access phpMyadmin

> <http://localhost:8081>
