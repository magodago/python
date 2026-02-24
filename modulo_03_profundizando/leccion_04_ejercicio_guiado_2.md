# Ejercicio guiado 2

## Objetivos
- Familiarizar al estudiante con la manipulación de listas complejas y su uso en funciones.
- Introducir la utilización de bucles anidados para procesar datos en Python.

## Contenido
En esta lección, profundizaremos en el manejo avanzado de listas. Veremos cómo crear, modificar y manipular listas complejas utilizando diversas técnicas. Además, exploraremos el uso de bucles anidados para realizar operaciones sobre elementos dentro de estas estructuras de datos. Este conocimiento es fundamental para procesar grandes cantidades de datos de manera eficiente en Python.

Para ilustrar estos conceptos, veremos ejemplos prácticos donde se crean listas multidimensionales y luego se manipulan utilizando bucles anidados. Esto permitirá al estudiante comprender cómo trabajar con datos estructurados complejos y realizar operaciones sobre ellos de manera eficiente.

## Ejercicio
Dado el siguiente código:

```python
def procesar_datos(datos):
    resultados = []
    for lista in datos:
        nueva_lista = [elemento * 2 for elemento in lista]
        resultados.append(nueva_lista)
    return resultados

datos = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
```

Modifica el código para que en lugar de multiplicar cada elemento por 2, sume 1 a cada elemento y luego multiplique el resultado por 3. Luego, aplica esta función a una nueva lista de datos multidimensionales.

## Resumen
- Se aprendió a manipular listas complejas mediante la creación y modificación.
- Se introdujo el uso de bucles anidados para procesar elementos dentro de estas estructuras.
- Se practicó la aplicación de operaciones en listas multidimensionales utilizando funciones.