# Laravel Study

Hi! It's my study about Laravel 7 using Docker (Compose file version 3.5)

MySQL 5.7

PHP 7.2

Apache 2.4.38 

Debian 10.4

I've created simple crud for Contacts to study how to use MVC pattern, Migration and Route which has attributes:

first_name',  
'last_name',  
'email',  
'city',  
'country',  
'job_title'

This study is based on these articles

[https://dev.to/veevidify/docker-compose-up-your-entire-laravel-apache-mysql-development-environment-45ea](https://dev.to/veevidify/docker-compose-up-your-entire-laravel-apache-mysql-development-environment-45ea)
[https://medium.com/techiediaries-com/laravel-7-crud-tutorial-build-a-crud-app-with-mysql-and-bootstrap-4-4ed8e94f2db0](https://medium.com/techiediaries-com/laravel-7-crud-tutorial-build-a-crud-app-with-mysql-and-bootstrap-4-4ed8e94f2db0)

# Commands to execute outside of the container

`docker-compose build`

`docker-compose up -d`

`docker exec -it laravel-app bash -c "sudo -u devuser /bin/bash" `

# Commands to execute inside of the container

`composer install`

`php artisan key:generate`

`php artisan migrate`

`composer require laravel/ui`

`php artisan ui vue `

`npm install && npm run dev`

`php artisan ui bootstrap`

`npm install && npm run dev`

`npm uninstall popper.js && npm i @popperjs/core`

`npm install popper.js –save`
