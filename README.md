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
http://172.67.0.5/api
```

## Adminer

```
http://172.67.0.6:8080/?server=db&username=api-platform&db=api
```

## Mongo Express

```
http://172.67.0.7:8081/
```