<h1>Requisitos iniciales del programa</h1>

##Proyecto empresas

creo el proyecto nuevo 
``` shell
laravel new empresas
 ```

###Requisitos
##R1 Instalar autentificacion 

1. Instalamos el paquete laravel/breeze

``` shell
composer require laravel/breeze
 ```

 2. publicar las rutas, vistas y controladores

``` shell
 php artisan breeze:install
 ```
##creara una carpeta nueva vendor/laravel/breeze

3. instalo la herramientas de front (tailwind)

``` shell
 npm install
 ```
4. ejecutamos el servidor de base de datos en el fichero docker-compose.yml
   ubicado en el directorio principal del proyecto

``` shell
 docker compose up -d
 ```

5. configuro el fichero ***.env*** para la base de datos

``` shell

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=empresa
DB_USERNAME=efra
DB_PASSWORD=efrain

```

6. ejecuto las migraciones

``` shell

php artisan migrate

```

7. arranco las herramientas del cliente 

``` shell

npm run dev

```

8. verificamos que este todo bien instalado

``` shell



```
