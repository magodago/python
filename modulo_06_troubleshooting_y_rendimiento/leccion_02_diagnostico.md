# Diagnostico

- Comprender los métodos básicos de diagnóstico de errores en Python.
- Identificar y corregir problemas comunes que afectan el rendimiento del código.

En esta lección, aprenderemos a diagnosticar problemas comunes en nuestro código Python. El primer paso es entender cómo interpretar las excepciones y mensajes de error proporcionados por la consola. Estos nos indican qué parte del código está causando un problema y qué tipo de error se ha producido. Para mejorar el rendimiento, es crucial identificar operaciones lentas o innecesarias en nuestro código. Usaremos herramientas de depuración como `print()` y módulos como `cProfile` para analizar la eficiencia del código.

Ejercicio: Analiza el siguiente fragmento de código y utiliza las herramientas aprendidas para identificar y corregir los posibles problemas:

```python
def calcular_factorial(n):
    if n == 0:
        return 1
    else:
        return n * calcular_factorial(n - 1)

print(calcular_factorial(5))
```

Resumen:
- Los mensajes de error son clave para diagnosticar problemas en Python.
- Herramientas como `cProfile` ayudan a identificar operaciones lentas y mejorar el rendimiento.