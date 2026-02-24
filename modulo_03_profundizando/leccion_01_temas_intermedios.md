# Temas intermedios

- Entender la utilización de decoradores en Python.
- Aprender a trabajar con módulos y paquetes externos.

Python nos ofrece una gran flexibilidad gracias a sus decoradores, que son funciones que toman otra función como argumento y permiten modificar su comportamiento sin cambiar su definición original. Los decoradores son útiles para agregar funcionalidades comunes a múltiples funciones de manera concisa. Por ejemplo, podríamos crear un decorador para medir el tiempo de ejecución de una función:

```python
import time

def timer_decorator(func):
    def wrapper(*args, **kwargs):
        start_time = time.time()
        result = func(*args, **kwargs)
        end_time = time.time()
        print(f"Tiempo de ejecución: {end_time - start_time} segundos")
        return result
    return wrapper

@timer_decorator
def ejemplo_funcion():
    # Código de la función
    pass

ejemplo_funcion()
```

Para trabajar con módulos y paquetes externos, es crucial entender cómo importar y utilizar funcionalidades de bibliotecas como NumPy o Pandas. Por ejemplo, para usar NumPy en un proyecto, primero necesitamos instalarlo si no está disponible en nuestro entorno:

```bash
pip install numpy
```

Luego, podemos importarlo en Python y usar sus funciones directamente:

```python
import numpy as np

# Crear un array de numpy
array = np.array([1, 2, 3])

print(array)
```

Este código muestra cómo trabajar con NumPy para crear y manipular arrays.

- Decoradores permiten modificar el comportamiento de funciones sin alterar su definición original.
- Los módulos y paquetes externos como NumPy pueden ser importados e integrados en proyectos Python.