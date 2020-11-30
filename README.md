# Lab7, docker-compose
Simple app showing phpinfo on docker containers, based on docker-compose.

## Description
App provides simple LAMP (Apache+PHP+MySQL) environment. WWW root directory is mounted from ./DocumentRoot directory. Database is stored in mysqldb volume. On initial run compose builds image based on php:apache and Dockerfile, installing mysqli extension allowing for connection to database.

## Running app
Clone repository and run `docker-compose up` in main directory.  Run `docker-compose down` to stop application.
