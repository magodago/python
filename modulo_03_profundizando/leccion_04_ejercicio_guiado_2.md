# Ejercicio guiado 2

## Objetivos
- Comprender la utilización de decoradores en Python y su aplicación práctica.
- Implementar una función que muestre el uso de un decorador para medir el tiempo de ejecución.

## Contenido
En esta lección profundizaremos en la utilidad de los decoradores, una característica poderosa de Python que nos permite modificar o extender las funcionalidades de funciones y métodos. Los decoradores son útiles para agregar funcionalidades comunes a múltiples funciones sin repetir código. En este ejercicio práctico, aprenderemos cómo crear un decorador para medir el tiempo de ejecución de una función, lo que nos permitirá evaluar la eficiencia del rendimiento de nuestro código.

## Ejercicio
Implementa un decorador llamado `tiempo` que muestre cuánto tiempo tarda en ejecutarse una función. Luego, aplica este decorador a una función que realice alguna tarea compleja, como calcular el factorial de un número grande. Por ejemplo:

```python
import time

def tiempo(func):
    def wrapper(*args, **kwargs):
        inicio = time.time()
        resultado = func(*args, **kwargs)
        fin = time.time()
        print(f"Tiempo de ejecución: {fin - inicio} segundos")
        return resultado
    return wrapper

@tiempo
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))
```

## Resumen
- Los decoradores son una herramienta poderosa para agregar funcionalidades a funciones existentes.
- Se puede utilizar un decorador `tiempo` para medir el rendimiento de las funciones.