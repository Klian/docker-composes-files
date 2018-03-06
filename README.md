# Docker composes files
## MySQL
- Instala la imagen oficial de MySQL
- Para tener los datos persistentes, crear en el directorio donde vayamos a almacenarlo el directorio “data”

## Wordpress
- Instala la imagen oficial de Wordpress
- Crear el directorio “app” dentro del directorio donde tengamos el docker-compose.yml
- Nos enlaza con la imagen creada anteriormente de MySQL .
- Podemos configurar el nombre de la base de datos con la variable WORDPRESS_DB_NAME

## Laravel
- Utiliza la imagen php:7.1-apache
- Crear el directorio “app” dentro del directorio donde tengamos el docker-compose.yml, ahí meteremos todo el código de Laravel
