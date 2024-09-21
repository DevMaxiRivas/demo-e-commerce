
# E-Commerce

Proyecto modelo de un e-commerce con laravel10
1) Clonar el repositorio a local


## Configuracion XAMPP

Cambiar en el archivo en xampp\php\php.ini

`;extension=gd`

`;extension=zip`

por

`extension=gd`

`extension=zip`

## No Olvidar
Crear un archivo .env con las credenciales necesarias.

## Despliegue

Para desplegar el proyecto ejecutar los siguientes comandos

```bash
 composer install
 npm install
 php artisan key:generate
 php artisan migrate:fresh --seed
 php artisan storage:link
 php artisan serve
```

