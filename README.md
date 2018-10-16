# API Platform with Docker

s. https://api-platform.com/

## Container

* MariaDB
* Adminer
* PHP-FPM
* nginx

## Installation

```bash
$ docker-compose up
```

## API

```
http://172.65.0.4/api
```

## Adminer

```
http://172.65.0.6:8080/?server=db&username=api-platform&db=api
```