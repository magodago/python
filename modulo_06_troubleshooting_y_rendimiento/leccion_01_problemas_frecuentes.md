# Problemas frecuentes

## Contenido
En esta lección, abordaremos algunos de los problemas más frecuentes que se pueden encontrar al trabajar con Python y cómo resolverlos. Uno de estos problemas es la optimización del código para mejorar su rendimiento. A menudo, el código puede ser lento debido a la utilización ineficiente de bucles o funciones innecesarias. Otro problema común es la gestión de errores y excepciones, ya que no todos los errores se capturan correctamente, lo cual puede llevar a comportamientos inesperados en tu programa.

Para mejorar el rendimiento, es importante identificar las partes del código que consumen más tiempo y optimizarlas. Esto puede implicar reescribir ciertas funciones para utilizar métodos más eficientes o incluso cambiar la lógica de los algoritmos utilizados. Además, Python ofrece varias bibliotecas y herramientas como `timeit` para medir el rendimiento del código y `cProfile` para analizar la eficiencia.

## Ejercicio
Analiza el siguiente código y realiza las modificaciones necesarias para mejorar su rendimiento:

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

for i in range(365):
    print(factorial(i))
```

Tu tarea es reescribir la función `factorial` para que sea más eficiente y luego comparar el tiempo de ejecución antes y después de hacer las modificaciones.

## Resumen
- Identificar y optimizar partes del código que consumen más tiempo.
- Mejorar la gestión de errores y excepciones en el programa.