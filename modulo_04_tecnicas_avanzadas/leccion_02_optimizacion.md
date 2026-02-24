# Optimizacion

### Objetivos
- Comprender las técnicas de optimización para mejorar la eficiencia del código Python.
- Implementar algoritmos de optimización en programas prácticos.

### Contenido
La optimización es crucial para mejorar el rendimiento y la eficiencia de los programas escritos en Python. Algunas técnicas fundamentales incluyen la compresión de listas, el uso de decoradores `@lru_cache` para memoización, y la gestión adecuada de estructuras de datos. La comprensión de listas permite crear listas de manera más eficiente, evitando bucles innecesarios. El decorador `@lru_cache` es útil para acelerar funciones recursivas o que realizan cálculos costosos al almacenar y reutilizar resultados previos. Además, elegir la estructura de datos adecuada puede tener un gran impacto en el rendimiento del programa.

### Ejercicio
Implementa una función `fibonacci` utilizando memoización con el decorador `@lru_cache`. La función debe calcular los primeros 50 números de la secuencia de Fibonacci y medir el tiempo de ejecución antes y después de aplicar la optimización. Compara los tiempos y explica los resultados.

### Resumen
- La comprensión de listas y el uso de decoradores son técnicas efectivas para optimizar código Python.
- La memoización puede reducir significativamente el tiempo de ejecución en funciones recursivas o que realizan cálculos repetitivos.