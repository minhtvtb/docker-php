# Nginx PHP MySQL

Docker running Nginx, PHP-FPM, MySQL and PHPMyAdmin.

## Các image sử dụng:

* [Nginx](https://hub.docker.com/_/nginx/)
* [MySQL](https://hub.docker.com/_/mysql/)
* [PHP-FPM](https://hub.docker.com/r/nanoninja/php-fpm/)
* [PHPMyAdmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
* [Generate Certificate](https://hub.docker.com/r/jacoelho/generate-certificate/)

## Sử dụng:

1. Run :

    ```sh
    $ docker-compose up
    ```

2. Open your favorite browser :

    * [http://localhost:8888] (WEB)
    * [phpMyAdmin](http://localhost:8080/) (user: dev, pass: dev)

## Sắp xếp thư mục:

```sh
├── README.md
├── data
│   └── db
│       ├── dumps
│       └── mysql
├── docker-compose.yml
├── etc
│   ├── nginx
│   │   └── default.conf
│   ├── php
│   │   └── php.ini
│   └── ssl
└── web
    ├── app
    │    
    │  
    └── public
        └── index.php
```
