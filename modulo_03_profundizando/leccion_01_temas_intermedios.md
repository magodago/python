# Temas intermedios

- Comprender la utilización de decoradores en Python y sus aplicaciones prácticas.
- Implementar y utilizar clases y objetos avanzados para resolver problemas complejos.

Python nos permite mejorar la funcionalidad de nuestras funciones mediante el uso de decoradores, que son una forma elegante de modificar comportamientos de funciones o métodos. Un decorador es simplemente un patrón de diseño que permite a los programadores agregar nuevas capacidades a las funciones y clases existentes sin alterar su estructura.

Por ejemplo, podemos crear un decorador para medir el tiempo de ejecución de una función:

```python
import time

def timer_decorator(func):
    def wrapper():
        start_time = time.time()
        func()
        end_time = time.time()
        print(f"Tiempo de ejecución: {end_time - start_time} segundos")
    return wrapper

@timer_decorator
def mi_funcion():
    # Código a medir
    for _ in range(1000000):
        pass

mi_funcion()
```

Este decorador `timer_decorator` mide el tiempo que tarda en ejecutarse la función `mi_funcion`. La sintaxis `@timer_decorator` antes de definir `mi_funcion` indica que queremos aplicar este decorador a dicha función.

Para el ejercicio, implemente un decorador que registre las llamadas a una función y cuente cuántas veces se ha ejecutado. Luego, utilícelo en una función que genere números primos hasta cierto límite.

## Resumen
- Decoradores permiten extender funcionalidades de funciones o métodos sin modificar su estructura.
- Las clases avanzadas y objetos pueden ser utilizados para resolver problemas complejos mediante la encapsulación, herencia y polimorfismo.