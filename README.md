# Desafio_LiterAlura
Descripción del Proyecto
Este proyecto fue desarrollado utilizando Java, Spring Boot y PostgreSQL. La aplicación es una consola interactiva que permite a los usuarios realizar varias operaciones relacionadas con la gestión de libros y autores.

Funcionalidades
La aplicación incluye las siguientes funcionalidades básicas:

Buscar libro por título:

El usuario ingresa el nombre del libro que desea buscar.
La aplicación consulta la API para obtener información del libro y lo registra en la base de datos.


Listar libros registrados:

Muestra todos los libros registrados en la base de datos.
Ejemplo de libros: "Don Quixote", "Emma", "Pride and Prejudice", "Romeo and Juliet", etc.
Listar autores registrados:

Muestra todos los autores registrados en la plataforma.
Ejemplo: "Jane Austen", "Cervantes", "Shakespeare".
Listar autores vivos en un año específico:

El usuario ingresa un año y la aplicación muestra los autores que estaban vivos en ese año.
Ejemplo: Autores vivos en 1600.
Listar libros por idioma:

El usuario puede listar los libros según su idioma (ES, EN, FR, PT).
Ejemplo: Buscar libros en español (ES).
Manejo de Errores
Libro no encontrado:

Si el libro no es encontrado, se muestra un mensaje indicando que el libro no fue encontrado.
Ejemplo: Buscar "QOQOQOQOE" no devolverá resultados.
Evitar duplicados:

No se permite registrar el mismo libro más de una vez.
Ejemplo: Intentar registrar "Pride and Prejudice" nuevamente no será permitido.
Configuración del Proyecto

Prerrequisitos
Java 17
Maven
PostgreSQL
