php artisan make:controller Api/V1/PostController --api --model=Post

php artisan make:resource V1/PostResource


version 2
================

php artisan make:controller Api/V2/PostController --api --model=Post
php artisan make:resource V2/PostResource
php artisan make:resource V2/PostCollection

<!-- Instalando nueva herramienta -->
composer require laravel/sanctum
php artisan migrate

<!-- en postman -->
headers
accept      application/json

php artisan make:controller Api/LoginController