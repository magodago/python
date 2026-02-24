# Pruebas y validacion

- Comprender la importancia de pruebas y validación en el desarrollo de proyectos Python.
- Implementar técnicas básicas de pruebas unitarias utilizando `unittest` para asegurar la integridad del código.

Python es un lenguaje de programación versátil que se utiliza en una amplia gama de aplicaciones, desde desarrollo web hasta análisis de datos. Para garantizar que el código funcione correctamente y no contenga errores, es crucial realizar pruebas y validaciones sistemáticas. En esta lección, aprenderás a utilizar `unittest`, un framework incorporado en Python para escribir pruebas unitarias.

Para ilustrar cómo funciona la validación y las pruebas, vamos a crear una pequeña aplicación que realiza cálculos matemáticos básicos. Primero, definiremos una función simple que suma dos números:

```python
def sumar(a, b):
    return a + b
```

Luego, implementaremos pruebas unitarias utilizando `unittest` para verificar que la función `sumar` funcione correctamente con diferentes entradas:

```python
import unittest

class TestSuma(unittest.TestCase):

    def test_suma_positivos(self):
        self.assertEqual(sumar(1, 2), 3)

    def test_suma_negativos(self):
        self.assertEqual(sumar(-1, -1), -2)

    def test_suma_cero(self):
        self.assertEqual(sumar(0, 5), 5)

if __name__ == '__main__':
    unittest.main()
```

Este código define una clase `TestSuma` que hereda de `unittest.TestCase`. Dentro de esta clase, se definen tres métodos para pruebas: `test_suma_positivos`, `test_suma_negativos` y `test_suma_cero`. Cada método utiliza el decorador `@unittest.expectedFailure` para indicar si la prueba debería fallar o no. Finalmente, se ejecutan las pruebas con `unittest.main()`.

- Comprender cómo implementar pruebas unitarias utilizando `unittest`.
- Verificar que una función básica funcione correctamente mediante pruebas de validación.