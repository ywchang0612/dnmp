# dnmp
run nginx + php + MySQL (MariaDB) on Docker

Build Service
``` sh
$ docker-compose up
```

Install pdo mysql
``` sh
$ docker-compose exec php docker-php-ext-install pdo_mysql
```

Install mysqli
``` sh
$ docker-compose exec php docker-php-ext-install mysqli
```
