# Ejercicio guiado 2

### Objetivos
- Familiarizarse con la optimización de código Python.
- Aprender a utilizar listas y diccionarios de forma eficiente.

### Contenido
En esta lección profundizaremos en técnicas para optimizar el rendimiento del código Python. Es crucial entender cómo manejar datos estructurados de manera eficiente, especialmente cuando se trabaja con grandes volúmenes de información. Las listas y diccionarios son fundamentales en la programación Python, pero su uso no siempre es óptimo si no se comprenden completamente sus características y limitaciones.

Un aspecto importante a considerar es la elección entre usar una lista o un diccionario dependiendo del tipo de operación que se vaya a realizar. Las listas son ideales para operaciones de búsqueda lineal, mientras que los diccionarios ofrecen acceso rápido a elementos mediante claves, lo cual puede ser crucial en aplicaciones donde la velocidad es un factor determinante.

### Ejercicio
Dado el siguiente código:

```python
def contar_palabras(texto):
    palabras = texto.split()
    frecuencia = {}
    for palabra in palabras:
        if palabra in frecuencia:
            frecuencia[palabra] += 1
        else:
            frecuencia[palabra] = 1
    return frecuencia

texto = "Este es un ejemplo de un texto para contar las palabras. Este texto tiene varias palabras repetidas y algunas no."
print(contar_palabras(texto))
```

Optimice el código anterior para mejorar su eficiencia, considerando la utilización adecuada de listas y diccionarios.

### Resumen
- Se aprendió a evaluar la elección entre usar listas o diccionarios según las operaciones necesarias.
- Se optimizó un código existente para contar el número de ocurrencias de cada palabra en un texto, mejorando su eficiencia.