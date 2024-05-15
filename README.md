# DESKTR

Book Sales & Distribution Management Software

[![Laravel](https://img.shields.io/badge/Laravel-8.x-ff2d20.svg)](https://laravel.com/docs/8.x)
[![PHP](https://img.shields.io/badge/PHP-7.3.x-777bb3.svg)](https://www.w3schools.com/php/default.asp)
[![MySQL](https://img.shields.io/badge/MySQL-10.4.x-ef7b00.svg)](https://www.w3schools.com/mysql/default.asp)

## Installation

```
$ composer create-project laravel/laravel:^8.0 DESKTR

$ cd DESKTR

$ php artisan serve
```

## Setup
```
$ git clone https://github.com/2gbeh/DESKTR.git

$ cd DESKTR

$ composer install

$ npm install (optional)

$ php artisan key:generate

$ php artisan serve
```

## Usage

1. Start `Apache Server` and visit [http://localhost/phpmyadmin](http://localhost/phpmyadmin/)

2. Create a new database `desktr`

3. Import database dump [desktr.sql](./database/desktr.sql)

4. Copy `.env.example` to `.env` and update content where applicable

```
APP_DEBUG=true
DB_USERNAME=${database_username}
DB_PASSWORD=${database_password}
```

5. Visit http://127.0.0.1:8000

## Documentation

![Screenshot](./public/social-preview.png)
