## Laravel For Absolute Beginners Course Level 2 Starter Repo

<img src="https://img-c.udemycdn.com/course/750x422/5896146_26e7_2.jpg">

**Created By :** Mahmoud Anwar
**Email :** Engsahaly@gmail.com

This is the main readme file for the starter code used in laravel for absolute beginners course on Udemy (Level 2)

## Installation

To get started, clone this repository.

```
git clone https://github.com/engsahaly/laravel_course_level_2_starter_repo.git
```

Next, copy your `.env.example` file as `.env` and configure your Database connection.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YOUR-DATABASE-NAME
DB_USERNAME=YOUR-DATABASE-USERNAME
DB_PASSWORD=YOUR-DATABASE-PASSWROD
```

## Run Packages and helpers

You have to all used packages and load helpers as below.

```
composer install
npm install
npm run build
```

## Generate new application key

You have to generate new application key as below.

```
php artisan key:generate
```

## Run Migrations

You have to run all the migration files included with the project and also run seeders as below.

```
php artisan migrate
```
