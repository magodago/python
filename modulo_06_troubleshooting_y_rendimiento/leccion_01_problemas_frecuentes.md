# Problemas frecuentes

## Contenido
En esta lección abordaremos algunos problemas frecuentes que pueden surgir al trabajar con Python y cómo resolverlos. Uno de los problemas más comunes es la gestión de errores y excepciones, especialmente cuando se trabaja con archivos o bases de datos. Otro problema común es el rendimiento del código, ya que Python puede ser lento en ciertas operaciones intensivas como la manipulación de grandes conjuntos de datos o cálculos numéricos intensivos.

Para manejar errores y excepciones, es importante entender cómo usar las sentencias `try`, `except` y `finally`. Estas permiten capturar y tratar excepciones que puedan surgir durante la ejecución del código. Por ejemplo:

```python
try:
    with open('archivo.txt', 'r') as file:
        contenido = file.read()
except FileNotFoundError:
    print("El archivo no existe.")
else:
    print(contenido)
finally:
    print("Operación finalizada.")
```

Para mejorar el rendimiento, se pueden utilizar técnicas como la optimización del código mediante el uso de comprensiones de lista o la implementación de algoritmos más eficientes. Además, es recomendable utilizar bibliotecas específicas para tareas intensivas, como NumPy y Pandas, que están optimizadas para manejar grandes cantidades de datos.

## Ejercicio
Implementa un programa en Python que lea un archivo CSV con datos numéricos y calcule la media de los valores. Utiliza comprensiones de lista para mejorar el rendimiento del cálculo de la media. Maneja posibles excepciones como `FileNotFoundError` o `ValueError`.

## Resumen
- Se aprende a manejar errores y excepciones utilizando sentencias `try`, `except` y `finally`.
- Se optimiza el rendimiento mediante técnicas como el uso de comprensiones de lista y la selección adecuada de bibliotecas.
- Se mejora la eficiencia al trabajar con grandes conjuntos de datos.