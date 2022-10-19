## Laravel 9 Complete Blog

## Requirements
•	PHP 8.0 or higher <br>

## Usage <br>
Setting up your development environment on your local machine: <br>
```
git clone https://github.com/AATezgel/laravel-blog-v0.1.git
cd laravel-blog-v0.1
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```

## Before starting <br>
Create a database <br>
```
mysql
create database laravelblog;
exit;
```

Setup your database credentials in the .env file <br>
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

Migrate the tables
```
php artisan migrate
```

