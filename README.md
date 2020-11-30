# Lab7, docker-compose

## Opis
Tutaj znajduje się aplikacja wykorzystująca środowisko LAMP (Apache, MySQL, PHP). 
App provides simple LAMP (Apache+PHP+MySQL) environment. WWW root directory is mounted from ./DocumentRoot directory. Database is stored in mysqldb volume. On initial run compose builds image based on php:apache and Dockerfile, installing mysqli extension allowing for connection to database.

## Uruchamianie aplikacji
W folderze z rozpakowaną/sklonowaną aplikacją należy wykonać komendę `docker-compose up`.
Analogicznie `docker-compose dowm` wyłącza aplikację.
