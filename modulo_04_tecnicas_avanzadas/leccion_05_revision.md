# Revision

### Objetivos
- Analizar y aplicar técnicas avanzadas de programación en Python.
- Mejorar la eficiencia del código mediante optimizaciones y mejores prácticas.

### Contenido
En esta lección, se revisará el uso de decoradores y generadores en Python. Los decoradores son una técnica poderosa que permite modificar o extender las funcionalidades de funciones o métodos sin alterar su estructura original. Por otro lado, los generadores permiten crear iteradores que producen secuencias de datos de manera eficiente, utilizando menos memoria y recursos.

Los decoradores se utilizan comúnmente para añadir funcionalidades como el control de acceso a métodos, la medición del tiempo de ejecución o la verificación de errores. Por ejemplo, un decorador puede ser usado para loggear información sobre las llamadas a una función:

```python
def log_function_call(func):
    def wrapper(*args, **kwargs):
        print(f"Llamada a {func.__name__} con argumentos: {args}, {kwargs}")
        return func(*args, **kwargs)
    return wrapper

@log_function_call
def suma(a, b):
    return a + b

suma(3, 4)
```

Los generadores, por su parte, permiten crear iteradores que producen valores de manera on-demand. Esto es especialmente útil cuando se trabaja con grandes conjuntos de datos o en situaciones donde la memoria sea un factor limitante:

```python
def generar_numeros(n):
    i = 0
    while i < n:
        yield i
        i += 1

for numero in generar_numeros(5):
    print(numero)
```

### Ejercicio
Escribe una función que use un decorador para medir el tiempo de ejecución de otra función. Luego, aplica este decorador a una función que genere y devuelva los primeros 20 números primos.

### Resumen
- Decoradores permiten extender las funcionalidades de funciones o métodos.
- Generadores son útiles para crear iteradores eficientes que producen datos on-demand.