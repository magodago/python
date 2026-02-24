# Ejercicio guiado 2

## Objetivos
- Implementar funciones recursivas de manera efectiva.
- Comprender y utilizar la estructura de datos diccionarios para almacenar información dinámica.

## Contenido
En esta lección profundizaremos en el uso de funciones recursivas, una técnica muy poderosa que permite a las funciones llamar a sí mismas durante su ejecución. Las funciones recursivas son útiles para resolver problemas que se pueden dividir en subproblemas similares. Además, aprenderemos cómo utilizar diccionarios en Python para almacenar y acceder a datos de manera eficiente, lo cual es especialmente útil cuando necesitamos manipular conjuntos de datos dinámicos o cuando queremos evitar cálculos repetidos.

Un ejemplo clásico de recursividad es el cálculo del factorial de un número. En lugar de usar un bucle, podemos definir una función que se llame a sí misma hasta alcanzar la condición base. Por otro lado, los diccionarios nos permiten almacenar pares clave-valor, lo cual puede ser muy útil para resolver problemas donde necesitamos acceder rápidamente a datos basados en ciertas condiciones o para optimizar el rendimiento de nuestro código.

## Ejercicio
Escribe una función recursiva que calcule el factorial de un número. Luego, implementa un diccionario para almacenar y devolver los resultados previos del cálculo del factorial, evitando así realizar cálculos repetidos. Por ejemplo:

```python
def factorial(n, memo={}):
    if n in memo:
        return memo[n]
    elif n == 0 or n == 1:
        memo[n] = 1
        return 1
    else:
        resultado = n * factorial(n - 1)
        memo[n] = resultado
        return resultado

# Prueba la función con algunos valores
print(factorial(5))  # Debería imprimir 120
```

## Resumen
- Las funciones recursivas son útiles para resolver problemas que pueden ser divididos en subproblemas similares.
- Los diccionarios en Python permiten almacenar y acceder a datos de manera eficiente, especialmente útil para evitar cálculos repetidos.