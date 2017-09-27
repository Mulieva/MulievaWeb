# MulievaWeb
Aplicativo web (desarrollado en Laravel)


Intalaciòn de repositorio

1. clonar repositorio de git hub, a su pc

2. Actualizar composer, mediante la terminal (o consola dos) , con la ubicacion de su proyecto laravel.

composer update

3. Generar el archivo de configuracion .env

copy .env.example .env


APP_NAME=Mulieva
.... 

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=mulieva   
DB_USERNAME=postgres
DB_PASSWORD=12345


Nota: en este adecuar con el nombre de la BD de su motor postgres, usuario y password correspondiente.

4. Generar la key de laravel

php artisan key:generate

5. Correr migraciones

php artisan migrate --seed
