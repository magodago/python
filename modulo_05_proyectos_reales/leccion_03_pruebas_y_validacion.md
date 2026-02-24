# Pruebas y validacion

- Comprender la importancia de pruebas y validación en el desarrollo de proyectos Python.
- Implementar métodos de prueba básicos utilizando las bibliotecas estándar de Python.

Python es un lenguaje de programación versátil que se utiliza ampliamente en diversas aplicaciones, desde desarrollo web hasta ciencia de datos. Sin embargo, para garantizar que el código funcione correctamente y esté libre de errores, es crucial implementar pruebas y validación. Las pruebas permiten verificar que las funciones y métodos del programa funcionan como se espera, lo cual es fundamental para mantener la calidad del software.

Para realizar pruebas en Python, podemos utilizar las herramientas integradas del lenguaje, como `assert`, o bibliotecas más avanzadas como `unittest` e `pytest`. Estas bibliotecas nos permiten escribir casos de prueba que se ejecutan automáticamente y nos informan sobre el estado del código. Por ejemplo, con `unittest`, podemos definir pruebas unitarias que verifican la funcionalidad individual de las partes más pequeñas del programa.

### Ejercicio

Implementa una función en Python que calcule el área de un círculo dado su radio. Luego, escribe pruebas utilizando la biblioteca `unittest` para verificar que la función devuelva los valores correctos para diferentes radios.

```python
import unittest

def area_circulo(radio):
    return 3.14 * (radio ** 2)

class TestAreaCirculo(unittest.TestCase):
    def test_area_circulo(self):
        self.assertEqual(area_circulo(0), 0)
        self.assertAlmostEqual(area_circulo(1), 3.14, places=2)
        self.assertAlmostEqual(area_circulo(5), 78.5, places=2)

if __name__ == '__main__':
    unittest.main()
```

### Resumen
- Pruebas son esenciales para verificar que el código funcione correctamente.
- Se puede utilizar `unittest` o `pytest` para implementar pruebas en Python.
- Las pruebas ayudan a mantener la calidad del software y facilitan la detección de errores.