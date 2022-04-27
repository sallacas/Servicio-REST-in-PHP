# Servicio restful PHP

Para poder correr el servicio se debe agregar a la carpeta del XAMP, WAMP, LAMP, etc. Esa será la ruta de ejecución

## Para la base de datos

Se agrega el .SQL con las tablas, se debe insertar al menos un valor en la tabla de roles para que no genere error
El nombre de la base de datos se puede ver/modificar en el archivo config.php

## Para la ejecución

Se anexa un .postman_collection con los json para poder ejecutar
```json
 La ruta de ejecución es el localhost/post.php
```

## Estructura
* GET: post.php
* GET by ID: post.php/{id}
* POST: post.php
* PUT: post.php
* DELETE: post.php/{id}
