# Temas intermedios

## Objetivos
- Comprender y aplicar la programación orientada a objetos en Python.
- Implementar manejo de excepciones para mejorar la robustez del código.

## Contenido
En esta lección profundizaremos en dos temas intermedios esenciales: programación orientada a objetos (POO) y manejo de excepciones. La POO nos permitirá organizar nuestro código de manera más estructurada, reutilizable y modular. Podremos definir clases con atributos y métodos para modelar entidades del mundo real, así como heredar comportamientos entre clases.

El manejo de excepciones es crucial para construir aplicaciones robustas. Veremos cómo capturar errores utilizando bloques `try`, `except` y `finally`. También aprenderemos a definir nuestras propias excepciones personalizadas para manejar situaciones específicas que puedan surgir durante la ejecución del programa.

## Ejercicio
Crea una clase `Libro` con atributos como título, autor, año de publicación y métodos para modificar estos atributos. Implementa un método `calcular_antiguedad()` que devuelva cuántos años ha pasado desde su publicación hasta la fecha actual. Luego, crea una función `mostrar_informacion()` en la clase `Libro` que imprima toda la información del libro.

A continuación, maneja posibles errores en la función `mostrar_informacion()` utilizando bloques `try`, `except` y `finally`. Por ejemplo, si el atributo `año_de_publicacion` no es un número válido, captura la excepción correspondiente y muestra un mensaje de error.

## Resumen
- La programación orientada a objetos permite organizar código en clases y objetos.
- El manejo de excepciones ayuda a construir aplicaciones más robustas al capturar y manejar errores.