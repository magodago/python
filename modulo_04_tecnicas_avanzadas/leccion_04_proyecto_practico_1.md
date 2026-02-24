# Proyecto practico 1

## Objetivos
- Desarrollar un proyecto práctico que implemente técnicas avanzadas de Python.
- Mejorar la capacidad para resolver problemas complejos utilizando programación orientada a objetos.

## Contenido
En esta lección, se trabajará en el desarrollo de una aplicación simple de gestión de biblioteca. Se utilizarán conceptos como herencia, polimorfismo y manejo de excepciones para organizar los diferentes tipos de recursos (libros, revistas) y sus métodos comunes. Además, se implementarán funciones avanzadas como la búsqueda por autor o título, y el control de prestamos y devoluciones.

Para lograr esto, primero se definirán las clases base y derivadas que representen los diferentes tipos de recursos. Luego, se desarrollará una interfaz para interactuar con la biblioteca, permitiendo al usuario realizar operaciones como buscar un recurso específico, prestarlo o devolverlo. Se abordarán también aspectos de manejo de errores y validación de datos.

## Ejercicio
Implemente una clase `Libro` que herede de una clase base `Recurso`. La clase `Libro` debe tener atributos como título, autor y año de publicación. Implemente métodos para obtener y establecer estos atributos, así como un método `mostrar_informacion()` que imprima la información del libro.

Luego, cree una subclase `Revista` que también herede de `Recurso`. Esta clase debe incluir adicionalmente los atributos `edicion` y `mes_publicacion`. Implemente métodos para estos atributos y un método `mostrar_informacion()` propio.

Finalmente, implemente una función principal que permita al usuario interactuar con la biblioteca, realizando operaciones como buscar un recurso, prestarlo o devolverlo. Utilice excepciones para manejar casos en los que el libro no esté disponible o se realicen operaciones inválidas.

## Resumen
- Se desarrolló una aplicación de gestión de biblioteca utilizando herencia y polimorfismo.
- Se implementaron clases para libros y revistas, con métodos comunes y específicos.
- Se trabajó en la interfaz de usuario y el manejo de excepciones para mejorar la robustez del programa.