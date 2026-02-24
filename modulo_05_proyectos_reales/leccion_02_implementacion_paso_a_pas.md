# Implementacion paso a paso

## Objetivos
- Implementar un proyecto real que permita a los estudiantes aplicar conceptos de programación orientada a objetos.
- Familiarizar a los estudiantes con la integración de diferentes módulos y paquetes en Python.

## Contenido
En esta lección, se continuará el desarrollo de un sistema simple de gestión de biblioteca. Los estudiantes aprenderán cómo estructurar clases y métodos para representar libros, usuarios y prestamos. Se explorará la importancia del encapsulamiento y herencia en este contexto. Además, se integrarán módulos como `datetime` para gestionar fechas y horas, y se discutirá la utilización de archivos JSON para persistir datos.

## Ejercicio
Desarrolla una clase `Prestamo` que tenga los siguientes atributos: `id_prestamo`, `libro`, `usuario`, `fecha_prestamo`, `fecha_devolucion`. Implementa un método `generar_recibo` que devuelva un string con la información del préstamo en formato legible. Utiliza archivos JSON para almacenar y recuperar los datos de los préstamos realizados.

## Resumen
- Se ha desarrollado una clase `Prestamo` que maneja la información relacionada con el préstamo de libros.
- Se ha integrado el uso de archivos JSON para persistir la información de los préstamos.
- Se ha aplicado el concepto de encapsulamiento y se ha explorado la importación de módulos en Python.