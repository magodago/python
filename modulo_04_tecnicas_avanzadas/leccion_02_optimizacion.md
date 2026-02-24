# Optimizacion

### Objetivos
- Comprender las técnicas de optimización en Python para mejorar la eficiencia del código.
- Implementar algoritmos de optimización en programas prácticos.

### Contenido
La optimización es crucial para mejorar el rendimiento y eficiencia de los programas escritos en Python. Una de las técnicas más efectivas es el uso de comprensiones de listas, que permiten crear listas de manera concisa y eficiente. Por ejemplo:

```python
# Sin comprensión de lista
nueva_lista = []
for i in range(10):
    nueva_lista.append(i * 2)

# Con comprensión de lista
nueva_lista = [i * 2 for i in range(10)]
```

Además, el uso de decoradores como `lru_cache` puede acelerar significativamente la ejecución de funciones recursivas o que realizan cálculos intensivos. Por ejemplo:

```python
from functools import lru_cache

@lru_cache(maxsize=32)
def fib(n):
    if n < 2:
        return n
    return fib(n-1) + fib(n-2)

print(fib(30))
```

Estas técnicas permiten reducir el tiempo de ejecución y la complejidad del código, lo que resulta en un mejor rendimiento general.

### Ejercicio
Escribe una función que calcule los primeros 50 números de la secuencia de Fibonacci utilizando comprensiones de listas. Luego, implementa la misma función usando el decorador `lru_cache` para optimizar el cálculo. Mide y compara el tiempo de ejecución de ambas versiones.

### Resumen
- La utilización de comprensiones de listas puede mejorar significativamente la eficiencia del código.
- El uso del decorador `lru_cache` ayuda a acelerar funciones recursivas o intensivas en cálculos.