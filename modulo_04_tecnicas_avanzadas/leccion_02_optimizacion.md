# Optimizacion

### Objetivos
- Comprender las técnicas de optimización en Python para mejorar la eficiencia del código.
- Implementar algoritmos de optimización en proyectos prácticos.

### Contenido
Las técnicas de optimización son cruciales para mejorar el rendimiento y la eficiencia del código Python. Una de las técnicas más utilizadas es la minimización del uso innecesario de recursos, como la memoria y los ciclos de CPU. Por ejemplo, en lugar de usar listas internas que pueden ser lentas para operaciones grandes, se puede optar por utilizar estructuras de datos más eficientes como NumPy arrays, que ofrecen un rendimiento significativamente mejorado.

Otra técnica es la memoización y la caché de funciones, especialmente útil en algoritmos recursivos o con muchos cálculos repetitivos. Python proporciona el módulo `functools` que ofrece decoradores para facilitar esta práctica. Por ejemplo:

```python
from functools import lru_cache

@lru_cache(maxsize=32)
def fib(n):
    if n < 2:
        return n
    return fib(n-1) + fib(n-2)
```

Este código calcula la secuencia de Fibonacci de manera eficiente, evitando cálculos repetidos a través del uso de caché.

### Ejercicio
Implemente una función que calcule el número de Fibonacci utilizando memoización. Luego, compare su rendimiento con una implementación recursiva sin optimización para n = 30 y n = 50. Mida el tiempo de ejecución en cada caso y explique los resultados obtenidos.

### Resumen
- La optimización en Python mejora significativamente la eficiencia del código.
- Se pueden utilizar estructuras de datos más eficientes como NumPy arrays para mejorar el rendimiento.
- La memoización es una técnica efectiva para evitar cálculos repetidos, especialmente en algoritmos recursivos.