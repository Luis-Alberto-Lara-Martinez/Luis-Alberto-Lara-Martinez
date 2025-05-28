# Symfony
Aquí se muestran todos los comandos necesarios para hacer un proyecto de Symfony (PHP)
## Crear nuevo proyecto
- Primero descargamos [Composer](https://getcomposer.org/download/), el cual es un gestor de dependencias. Nota: hay que tener una versión de PHP superior a la versión 8.1, sino la tienes instalada en tus variables de entorno, hazlo. Después ejecutamos estos dos comandos en la ruta en la que vayas a querer crear tu proyecto.
```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
```
```bash
php composer-setup.php
```
- Finalmente creamos nuestro proyecto con estos comandos. La opción webapp instala los paquetes necesarios para crear una aplicación web.
```bash
composer create-project symfony/skeleton nombreProyecto
```
```bash
cd nombreProyecto
```
```bash
composer require webapp
```
## Actualizar versión del proyecto
- Con este comando compruebas si alguna de las dependencias que usa tu proyecto tiene alguna actualización disponible.
```bash
composer outdated symfony/*
```
- Con este comando instalas las actualizaciones disponibles.
```bash
composer update symfony/*
```
## Ejecutar proyecto descargado de GitHub
- Es necesario reinstalar las librerias configuradas
```bash
composer install
```
