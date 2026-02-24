# Puntos clave

### Objetivos
- Comprender la utilización de decoradores en Python.
- Aprender a manejar excepciones de manera eficiente.

### Contenido
Los decoradores son una característica poderosa y versátil de Python que permiten modificar el comportamiento de funciones o métodos sin alterar su estructura. Un decorador es simplemente una función que toma otra función como argumento, agrega ciertas funcionalidades y devuelve la función modificada. Por ejemplo:

```python
def my_decorator(func):
    def wrapper():
        print("Algo antes")
        func()
        print("Algo después")
    return wrapper

@my_decorator
def say_hello():
    print("¡Hola!")

say_hello()
```

En este código, `my_decorator` es un decorador que agrega una funcionalidad adicional a la función `say_hello`. La sintaxis `@my_decorator` antes de la definición de `say_hello` indica que se debe aplicar el decorador a esa función.

Además, manejar excepciones de manera eficiente es crucial para evitar que el programa se detenga abruptamente. Python proporciona una serie de excepciones predefinidas y permite definir propias si es necesario. La estructura básica para manejar excepciones es:

```python
try:
    # Código susceptible a errores
except Excepcion1:
    # Manejo del error Excepcion1
except Excepcion2 as e:
    # Manejo del error Excepcion2 y acceso al mensaje de error con `e`
else:
    # Ejecutado si no se produce ninguna excepción
finally:
    # Ejecutado siempre, independientemente de si ocurrió una excepción o no
```

### Ejercicio
Escribe un decorador que registre el tiempo de ejecución de una función y lo imprima en la consola. Luego, aplica este decorador a una función que calcule los primeros 10 números de Fibonacci.

### Resumen
- Los decoradores permiten modificar el comportamiento de funciones sin alterar su estructura.
- Manejar excepciones eficientemente es crucial para evitar errores y mantener la fluidez del programa.