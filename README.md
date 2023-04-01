
## This APP is QRCode-based Lecture Exam Attendance Tracking System using Laravel 9

The code is a site to add exams and register students' attendance through a special code generated from their university Registration Number.

## Application requirements

- **[Node.js](https://nodejs.org/en/)**
- **[composer](https://getcomposer.org/)**
- **[xampp server v8.1](https://www.apachefriends.org/index.html)**
- **[laravel 9](https://laravel.com/)**
- **[Visual Studio Code](https://code.visualstudio.com/)**

## Application Install
- git clone git@github.com:Techbite-sudo/lats.git
- cd lats
- composer install
- copy .env.example to .env
- php artisan key:generate
- create database name lats on xampp server http://localhost/phpmyadmin/index.php?route=/server/databases.
- php artisan migrate:fresh
- php artisan db:seed
- php artisan serve
- http://localhost:8000 on browser
- You have two accounts to login email : administrator@gmail.com | password : administrator or email : teacher@gmail.com | password : teacher.

## Application Run
- //vercel link.

