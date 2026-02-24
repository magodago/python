# Temas intermedios

- Comprender la utilización de decoradores y su aplicación práctica.
- Familiarizarse con las excepciones y manejo de errores en Python.

En esta lección profundizaremos en dos temas intermedios esenciales: los decoradores y el manejo de excepciones. Los decoradores son una característica poderosa que permite modificar o extender la funcionalidad de funciones, métodos o clases sin alterar su código original. En Python, se utilizan con la sintaxis `@decorador` antes de la definición de una función. Por ejemplo:

```python
def mi_decorador(func):
    def wrapper():
        print("Antes de ejecutar la función")
        func()
        print("Después de ejecutar la función")
    return wrapper

@mi_decorador
def hola_mundo():
    print("¡Hola, mundo!")

hola_mundo()
```

El manejo de excepciones es crucial para desarrollar software robusto. Python proporciona una serie de excepciones predefinidas y permite definir nuestras propias excepciones heredando de la clase `Exception`. El uso adecuado de bloques `try`, `except`, `else` y `finally` ayuda a manejar errores de forma controlada, mejorando la experiencia del usuario y la estabilidad del programa.

Ejercicio: Implementa un decorador que mide el tiempo de ejecución de una función y muestra el resultado en consola. Luego, aplica este decorador a diferentes funciones matemáticas para observar cómo funciona.

- Comprender cómo funcionan los decoradores.
- Familiarizarse con la implementación y uso del manejo de excepciones.