# book-microservice
SI-PDI-EXAMEN

Nombre: Luis Briones
Fecha: 05/01/2023

Método HTTP        URL                Acción
  GET           /books/{id}      Buscar un libro por ID 
  GET           /books           Listar todos los libros 
  POST          /books           Inserter 
  PUT           /books/{id}      Actualizer 
  DELTE         /books/{id}      Eliminar
  
Tabla BOOKS:

public.books  
***********************
* id:serial           *
***********************
* isbn:varchar(16)    *
* title:varchar(128)  *
* author:varchar(64)  *
* price:numeric(6,2)  *
***********************

Crear una aplicación que permita realizar el CRUD de la base datos 
1. Componente(s) de negocio CDI para los servicios 
2. Componente(s) REST para el acceso remoto 
3. JSON como formato de datos 
4. Base de datos PostgreSQL 
5. Utilizar un pool de conexiones para el acceso a datos 
6. Utilizar como framework para acceso a datos Jdbi 3 (https://jdbi.org/) 
7. Incluir un archivo .bat (o .sh en Linux) que permita ejecutar 4 instancias de la aplicación 
8. Aplicar todas las recomendaciones posibles de la metodología de los 12 factores. 
