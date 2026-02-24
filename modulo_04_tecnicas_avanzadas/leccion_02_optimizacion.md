# Optimizacion

### Objetivos
- Comprender y aplicar técnicas de optimización para mejorar la eficiencia del código Python.
- Identificar y corregir posibles puntos de rendimiento en programas existentes.

### Contenido
La optimización es crucial para asegurar que el código Python funcione de manera eficiente, especialmente con grandes conjuntos de datos o aplicaciones complejas. En esta lección, se explorarán técnicas avanzadas como la utilización de listas comprensivas y funciones generadoras en lugar de bucles for tradicionales, así como el uso de módulos incorporados como `timeit` para medir y optimizar el rendimiento del código.

Además, se abordará cómo utilizar la biblioteca `numpy`, que proporciona estructuras de datos más eficientes (como arreglos multidimensionales) y funciones vectorizadas, lo cual puede resultar en un gran aumento de velocidad en operaciones numéricas. Se discutirá también el uso de decoradores para optimizar funciones y la gestión de memoria mediante técnicas como la reutilización de objetos.

### Ejercicio
Dado el siguiente código que calcula los primeros 1000 números primos:

```python
def es_primo(n):
    if n <= 1:
        return False
    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return False
    return True

primos = []
for num in range(2, 1000000):
    if es_primo(num):
        primos.append(num)
```

Optimiza este código utilizando técnicas vistas en la lección. Mide el tiempo de ejecución antes y después de la optimización.

### Resumen
- Se destacará la importancia de utilizar estructuras de datos más eficientes como los arreglos de `numpy`.
- Se resaltarán las ventajas de usar listas comprensivas y funciones generadoras.
- Los decoradores se presentarán como una herramienta útil para mejorar el rendimiento de las funciones.