## Ninja Studio Docker Stack

Docker compose for dev env

On board:
- Apache (latest)
- MariaDB (latest)
- PHP 8.3.4 RC1 + xDebug

PHP 8.3.4 RC1-fpm built in docker/Dockerfile and contains:
- GD --with-freetype --with-jpeg --with-webp
- mysqli
- xDebug
- Composer

First run:
- docker compose up

or:

- docker-compose up

Use Ctrl+C to stop Docker containers

Next usage:

- docker compose start\stop

or:

- docker-compose start\stop

MariaDB Defaults:
- User: root
- Pass: admin
- Host: db

Update your hosts file with: 
>127.0.0.1 site.local

> http://site.local

With best regards Serhii Herenko

Keywords:

Docker Apache MySQL PHP 8.3

Docker Apache MySQL php-fpm 8.3

Docker Apache MariaDB PHP 8.3

Docker Apache MariaDB php-fpm 8.3
