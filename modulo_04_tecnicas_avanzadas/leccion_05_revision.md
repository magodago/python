# Revision

## Objetivos
- Comprender y aplicar técnicas avanzadas de programación en Python.
- Analizar y optimizar código existente utilizando patrones de diseño.

## Contenido
En esta lección de tecnicas avanzadas, revisaremos el uso de decoradores y métodos de clase en Python. Los decoradores son una técnica poderosa que permite modificar o extender las funcionalidades de funciones o métodos sin alterar su estructura original. Por ejemplo, podemos usarlos para agregar funcionalidades como loggin, validación de entrada o cálculo de tiempo de ejecución.

Los métodos de clase permiten definir métodos que operan sobre la clase en sí misma, en lugar de instancias de la clase. Esto es útil cuando necesitamos acceder a atributos estáticos o realizar acciones que no requieren una instancia específica del objeto. Por ejemplo, podemos usarlos para inicializar datos compartidos entre todas las instancias de una clase.

## Ejercicio
Reescribe el siguiente código utilizando un decorador y métodos de clase:

```python
class Calculadora:
    def __init__(self):
        self.resultado = 0

    def suma(self, a, b):
        self.resultado += a + b
        return self.resultado

# Reescrito con decorador
def loggin(func):
    import logging
    logging.basicConfig(level=logging.INFO)

    def wrapper(*args, **kwargs):
        logging.info(f"Llamada a {func.__name__}({', '.join(map(str, args))})")
        resultado = func(*args, **kwargs)
        logging.info(f"Resultado: {resultado}")
        return resultado

    return wrapper

@loggin
def suma(a, b):
    return a + b

# Reescrito con método de clase
class Calculadora2:
    @classmethod
    def inicializar(cls):
        cls.resultado = 0

    def __call__(self, a, b):
        self.inicializar()
        self.resultado += a + b
        return self.resultado

calculadora = Calculadora2()
print(calculadora(5, 3))
```

## Resumen
- Los decoradores permiten extender funcionalidades de funciones o métodos.
- Los métodos de clase operan sobre la clase en sí y no requieren una instancia.