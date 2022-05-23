## About Confectionery
Confectionery is app which support suppliers during taking orders for baker. It allow to collect client's orders and generate delivery documents.

## Technologies stack
App was built in Laravel 8 with upgrade to 9 and Vue 3 frameworks. In project was used laravel's official packages:
- Sanctum
- Fortify

Other technologies: 
- axios
- dompdf
- vue router

## Live version

Actual link

[Link to LIVE VERSION](https://confectionery.frb.io)

## Installation
For locally deploy run:
- composer install
- cp .env.example .env

In .env file set variables:
- APP_URL=http://127.0.0.1
- SESSION_DOMAIN=127.0.0.1
- SESSION_DRIVER=cookie
- DB_HOST=mysql
- DB_USERNAME=sail
- DB_PASSWORD=password

After run commands:
- php artisan key:generate
- npm install

- sail up -d
- sail artisan migrate
- sail artisan db:seed
- sail artisan storage:link


- sail npm run dev

Open web browser at http://127.0.0.1

To stop docker container use:
- sail down

## Contact
kamildeveloper@protonmail.com
