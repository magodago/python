# Ejercicio guiado 2

## Objetivos
- Familiarizar al estudiante con la manipulación de listas y diccionarios en Python.
- Aprender a utilizar funciones para procesar datos complejos.

## Contenido
En esta lección, profundizaremos en el manejo de estructuras de datos más avanzadas como las listas y los diccionarios. Veremos cómo crear, modificar y acceder a estos tipos de datos, así como cómo usar funciones para realizar tareas específicas con ellos. Es importante entender que estas estructuras son fundamentales para la programación en Python y permiten manejar datos complejos de manera eficiente.

Por ejemplo, podríamos trabajar con una lista de diccionarios donde cada diccionario represente un libro con sus respectivas propiedades como título, autor y año de publicación. A través de funciones, podríamos implementar operaciones como buscar un libro por su título o calcular el promedio del año de publicación.

## Ejercicio
Dado el siguiente código:

```python
libros = [
    {"título": "El Señor de los Anillos", "autor": "J.R.R. Tolkien", "año": 1954},
    {"título": "Cien años de soledad", "autor": "Gabriel García Márquez", "año": 1967}
]
```

Desarrolla una función `promedio_anio_publicacion` que tome la lista `libros` como argumento y devuelva el promedio del año de publicación de todos los libros.

Luego, crea otra función `buscar_libro_por_titulo` que acepte tanto la lista `libros` como un título específico como argumentos. Esta función debe buscar si existe un libro con ese título en la lista y retornar el diccionario correspondiente o `None` si no se encuentra.

## Resumen
- Se aprendió a manipular listas y diccionarios para manejar datos complejos.
- Se desarrollaron funciones para procesar datos de manera eficiente.