# Implementacion paso a paso

## Objetivos
- Implementar un proyecto real que permita al usuario crear una lista de compras personalizada.
- Aprender a utilizar estructuras de datos como listas y diccionarios para gestionar el contenido de la lista de compras.

## Contenido
En esta lección, continuaremos con nuestro viaje hacia la implementación de proyectos reales en Python. Vamos a crear un programa que permita al usuario agregar, eliminar y visualizar artículos en una lista de compras personalizada. Este ejercicio no solo nos ayudará a practicar el manejo de listas y diccionarios, sino también a mejorar nuestras habilidades en la interacción con los usuarios a través de la entrada y salida estándar.

Para comenzar, definiremos una clase `ListaCompras` que contendrá métodos para agregar artículos (`agregar_articulo`), eliminar artículos (`eliminar_articulo`) y mostrar la lista actualizada (`mostrar_lista`). Cada artículo se almacenará en un diccionario con el nombre del artículo y su cantidad. Este diseño nos permitirá gestionar información detallada sobre cada artículo de manera eficiente.

## Ejercicio
Implementa una clase `ListaCompras` que permita al usuario realizar las siguientes acciones:
1. Agregar artículos a la lista de compras.
2. Eliminar artículos de la lista de compras.
3. Mostrar todos los artículos en la lista actualizada.

Puedes utilizar el siguiente código como punto de partida:

```python
class ListaCompras:
    def __init__(self):
        self.articulos = {}

    def agregar_articulo(self, nombre, cantidad):
        # Implementa este método para agregar un artículo a la lista

    def eliminar_articulo(self, nombre):
        # Implementa este método para eliminar un artículo de la lista

    def mostrar_lista(self):
        # Implementa este método para mostrar todos los artículos en la lista
```

## Resumen
- Se ha definido una clase `ListaCompras` que utiliza listas y diccionarios para gestionar la información de la lista de compras.
- El ejercicio consiste en completar métodos para agregar, eliminar y visualizar artículos en la lista de compras.