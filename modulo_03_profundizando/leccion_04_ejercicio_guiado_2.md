# Ejercicio guiado 2

## Objetivos
- Aprender a utilizar la biblioteca `collections` para trabajar con estructuras de datos avanzadas.
- Familiarizarse con el uso de `defaultdict`, `deque` y `Counter`.

## Contenido
En esta lección profundizaremos en la biblioteca `collections` de Python, que proporciona varias clases de colecciones adicionales más allá de las listas, tuplas y diccionarios. Específicamente, nos centraremos en tres estructuras de datos: `defaultdict`, `deque` y `Counter`. 

La clase `defaultdict` es una subclase de `dict` que sobrescribe el método `__missing__()` para devolver un valor predeterminado si se intenta acceder a una clave no existente. Esto puede ser muy útil en situaciones donde queremos inicializar automáticamente los valores de las claves.

El objeto `deque`, abreviatura de "double-ended queue", es una lista de doble extremo que permite añadir y eliminar elementos desde ambos lados con un tiempo de complejidad constante. Es particularmente útil para implementar colas y pila dinámicas.

Finalmente, la clase `Counter` es una subclase de `dict` diseñada para contar los elementos en una colección. Proporciona métodos útiles como `elements()`, `most_common()` y `subtract()` que facilitan el análisis de datos.

## Ejercicio
Implemente un programa que use `defaultdict` para contar las ocurrencias de palabras en un texto. Luego, utilice `deque` para simular una caja de correos electrónico donde se pueden añadir y eliminar mensajes por la izquierda (enviar) o la derecha (recibir). Por último, emplee `Counter` para analizar los elementos más comunes en una lista dada.

## Resumen
- Se aprendió a utilizar `defaultdict` para contar ocurrencias de palabras.
- Se exploró el uso de `deque` para manejar colas dinámicas.
- Se implementaron análisis de datos con la ayuda de `Counter`.