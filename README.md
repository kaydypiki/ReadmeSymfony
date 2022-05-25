# Práctica Symfony Final

## Descripción general del proyecto
Tendremos que desarrollar una aplicación usando el framework Symfony. En esta aplicación trabajaremos las funciones básicas **(Métodos** **CRUD)** y con relacion con las bases de datos.
## Cómo se usa el proyecto
Para poder trabajar con el proyecto necesitaremos tener **Symfony** para poder ser lanzado, para ello tambien tendremos que activar nuestro **XAMP** ( Para poder trabajar de manera local). Tendremos que tener creada nuestra base de datos con **SQLITE** y el codigo con **PHP** con sus respectivas plantillas. Lanzaremos nuestro proyecto de manera local y podremos trabajar con el.
## Requisitos del entorno de desarrollo
Para poder esta tarea lo que necesitaremos sera PHP, un editor de textos, tener Symfony instalado, Doctrine y el Composer. Para la base de datos utilizaremos SQLITE aunque cualquier gestor valdria aunque habría que tener en cuenta el script de la base de datos. 

## Guía de instalación y funcionamiento
1. Creamos el proyecto de Symfony. Primero instalamos Doctrine `composer require symfony/orm-pack` y `composer require --dev symfony/maker-bundle` . Para instalar el composer `composer install`

2. Descomentamos en el archivo *.env* las lineas de SQLITE para nuestro gestor de base de datos. Crearemos la base de datos con el comando `php bin/console doctrine:database:create` . Creamos el Entity `php bin/console make:entity`

3. Trabajaremos con nuestro editor de texto en nuestro proyecto creando las funciones y métodos pertinentes.

4. Una vez escribamos el Article.php haremos una migración para guardar los datos. Para hacer la migracion usar el comando `php bin/console make:migration` una vez creada la ejecutamos con el comando `php bin/console doctrine:migrations:migrate`.

6. Abriremos por ejemplo la consola de Git y abriremos nuestro proyecto con el comando  `symfony server:start`.
## Tecnologías utilizadas
1. [Symfony](https://symfony.com/doc/current/setup.html)
2. [PHP](https://www.php.net/manual/es/install.php)
3. [Visual Studio Code](https://code.visualstudio.com/)

## Autoría
**Carlos Fariña Subiela**
## Licencia
MIT License

## Cómo contribuir al proyecto
| GIT HUB | CORREO |
| ----------- | ----------- |
| kaydypiki  | charly.f@live.com|
