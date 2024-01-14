<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Expense Calculator

Expense calculator es una aplicacion para administrar gastos ya sea familiares o de algun negocio o entidad, su objetivo se basa en la simplesa hacia el usuario, esta aplicacion fue hecha con fines recreativos por su desarrollador, para aplicar conocimientos en Laravel, Mysql, Javascript, Alpinejs, Sass y css fuera de proyectos corporativos que no se pueden compartir por obvias razones. 


## Tecnologias utilizadas

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

- Laravel: Framework para construir el backend y frontend (serverside)
- Blade: Motor de plantillas de Laravel
- AlpineJS: Framework javascript para frontend
- Mysql: Motor de base de datos.
- Eloquent: ORM
- Bootstrap: Libreria css 

## Instalacion

Para instalar este proyecto necesitamos un entorno que tenga como requisito basico php8.1, composer, mysql 8 o superior y nodejs 18 o superior.
Puedes instalar estas herramientas individualmente en tu sistema operativo o hacer utilidad de devilbox que es una versatil herramienta que te permite ejecutar un entorno completo en muy simples pasos y solo necesitas docker.

### Primer paso agregar variables de entorno
En la raiz del repositorio tenemos un .env-example , tenemos que copia ese archivo y renombrarlo como .env, tenemos que modificar las variables de conexion a db, y a url segun nuestro entorno local, puede revisar la documentacion de laravel para mas ayuda o contactarme y lo asistire con gusto.

```bash
composer install
```
```bash
npm install
```
```bash
php artisan migrate
```