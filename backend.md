# Laravel

végpont - middlewatte - controller - service - model 

### Projekt létrehozása

 composer create-project laravel/laravel Bemutato


### Szerver indítás

    php artisan serve

### postman, insomnia, insomnium - adat megjelenítése   

### Új .env appkey generálás

    php artisan key:generate

### php artisan parancsok

    php artisan list

https://github.com/backend2026N

### composer ne vegye figyelembe a php verziót:

	composer install --ignore-platform-req=php

### stubok láthatósága

	php artisan stub:publish
	
## PHP 8.4 beállítása

php_save mappa -> régi php
php84 -> php 8.4

php84 php.ini.development -> php.ini

extensions = openssl
extensions = fileinfo
extensions = mbstring
extensions = zip
extension_dir = "ext"

path változtatás a környezeti változókban, vagy másolás -> php
