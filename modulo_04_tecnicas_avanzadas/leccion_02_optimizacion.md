# Optimizacion

### Objetivos
- Comprender y aplicar técnicas de optimización para mejorar la eficiencia del código Python.
- Implementar algoritmos de optimización en programas reales para reducir tiempos de ejecución.

### Contenido
La optimización es crucial para el desarrollo de software eficiente, especialmente cuando se trabaja con grandes volúmenes de datos o aplicaciones que requieren altas velocidades. En Python, existen varias técnicas y herramientas que pueden ser utilizadas para mejorar la velocidad y reducir el consumo de recursos. Entre estas técnicas destacan:

1. **Uso eficiente de bucles**: Aunque Python es un lenguaje interpretado, ciertos patrones de bucle pueden ser optimizados. Por ejemplo, el uso de comprensiones de lista en lugar de bucles `for` tradicionales puede mejorar significativamente la velocidad y la legibilidad del código.

2. **Memoización**: Esta técnica consiste en almacenar los resultados de funciones costosas para que no se repitan si las mismas entradas ocurren nuevamente, lo cual es muy útil en problemas recursivos o con componentes repetitivos. La biblioteca `functools` en Python proporciona la función `lru_cache` para implementar fácilmente esta técnica.

3. **Vectorización**: Utilizar librerías como NumPy y Pandas que permiten realizar operaciones matemáticas vectorizadas, lo cual es significativamente más rápido que el uso de bucles tradicionales en Python.

### Ejercicio
Implemente una función que calcule los primeros 100 números de la serie Fibonacci utilizando memoización. Compare el tiempo de ejecución con una implementación tradicional basada en un bucle `for`. Utilice el módulo `time` para medir el tiempo y compare los resultados.

### Resumen
- La optimización es fundamental para mejorar el rendimiento del código Python.
- Se pueden aplicar técnicas como la memoización y la vectorización para aumentar la eficiencia.
- El uso de comprensiones de lista y algoritmos eficientes puede reducir significativamente los tiempos de ejecución.