# Symfony
Aquí se muestran todos los comandos necesarios para hacer un proyecto de Symfony (PHP)
## Crear nuevo proyecto
- Primero descargamos [Composer](https://getcomposer.org/download/), el cual es un gestor de dependencias. Nota: hay que tener una versión de PHP superior a la versión 8.1, sino la tienes instalada en tus variables de entorno, hazlo. Después ejecutamos estos dos comandos donde vayas a querer crear tu proyecto.
```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
```
```bash
php composer-setup.php
```
## Ejecutar proyecto descargado de GitHub
- Es necesario reinstalar las librerias configuradas
```bash
composer install
```
