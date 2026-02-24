# Revision

## Objetivos
- Comprender y aplicar técnicas avanzadas de programación en Python.
- Analizar y optimizar código existente utilizando mejores prácticas.

## Contenido
En esta lección, se revisará el uso de decoradores y generadores para mejorar la eficiencia y funcionalidad del código. Los decoradores permiten modificar o extender las funciones existentes sin alterar su estructura original, lo que es útil en diversas situaciones como manejo de errores, loggin o autenticación. Por otro lado, los generadores son una forma eficiente de crear iteradores, permitiendo el procesamiento de grandes conjuntos de datos de manera más manejable y节省能源的小贴士。

## Ejercicio
Reescribe la función `calcular_factorial` utilizando un decorador para medir el tiempo de ejecución. Luego, compara su rendimiento con una versión no decorada.

```python
import time

def medir_tiempo(func):
    def wrapper(*args, **kwargs):
        inicio = time.time()
        resultado = func(*args, **kwargs)
        fin = time.time()
        print(f"Tiempo de ejecución: {fin - inicio} segundos")
        return resultado
    return wrapper

@medir_tiempo
def calcular_factorial(n):
    if n == 0:
        return 1
    else:
        return n * calcular_factorial(n-1)

# Prueba la función
print(calcular_factorial(5))
```

## Resumen
- Decoradores permiten modificar funciones existentes de manera eficiente.
- Generadores son útiles para manejar grandes conjuntos de datos de forma más manejable.