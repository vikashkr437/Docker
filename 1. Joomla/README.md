Welcome to Joomla,
Joomla is a free and open-source content management system (CMS) for publishing web content.
It is built on a model–view–controller web application framework that can be used independently of the CMS.

Joomla is written in PHP, uses object-oriented programming (OOP) techniques and software design patterns, stores data in a MySQL,
MS SQL, or PostgreSQL database, and includes features such as page caching, RSS feeds, printable versions of pages, news flashes,
blogs, search, and support for language internationalization.
This project contains a docker-compose.yml file which can be run from any system having docker-compose installed and in no time will be
able to set up Jooomla website with MySQL database server at its backend.


Joomla runs on port number 8085 of your Base OS

To access Database while sign up use:

MYSQL_ROOT_PASSWORD: vk01
MYSQL_USER: vikash
MYSQL_PASSWORD: vk01
MYSQL_DATABASE: jmdb

Download docker-compose version 3

First add this docker-compose.yml to a directory and from that directory:

To run the file :
docker-compose up

To stop the contaiers:
docker-compose stop

To close the program and remove the running containers :
docker-compose down
