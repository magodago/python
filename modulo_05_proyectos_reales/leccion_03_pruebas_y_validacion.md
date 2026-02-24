# Pruebas y validacion

- Comprender la importancia de pruebas y validación en el desarrollo de proyectos con Python.
- Implementar técnicas básicas de pruebas unitarias utilizando la biblioteca `unittest`.

Python es un lenguaje de programación versátil que se utiliza en una amplia gama de aplicaciones, desde desarrollo web hasta ciencia de datos. Sin embargo, para garantizar que el código funcione correctamente y mantenga su calidad a lo largo del tiempo, es crucial implementar pruebas y validación. Las pruebas permiten detectar errores temprano en el proceso de desarrollo, mejorando la confiabilidad del software.

En esta lección, se explorará cómo utilizar la biblioteca `unittest` para escribir pruebas unitarias en Python. `unittest` es parte estándar de la biblioteca de Python y proporciona una forma organizada de escribir pruebas que pueden ser ejecutadas fácilmente. Las pruebas unitarias evalúan si las unidades básicas del código (funciones, métodos) funcionan como se esperaba. A través de ejemplos prácticos, los estudiantes aprenderán a definir casos de prueba y a utilizar diferentes tipos de assertions para verificar el comportamiento de sus funciones.

### Ejercicio

Escribe un programa que calcule la suma de dos números enteros. Luego, implementa pruebas unitarias utilizando `unittest` para verificar que tu función funcione correctamente con diversos conjuntos de datos:

```python
import unittest

def suma(a, b):
    return a + b

class TestSuma(unittest.TestCase):
    def test_suma_positivos(self):
        self.assertEqual(suma(2, 3), 5)

    def test_suma_negativos(self):
        self.assertEqual(suma(-1, -1), -2)

    def test_suma_cero(self):
        self.assertEqual(suma(0, 0), 0)

if __name__ == '__main__':
    unittest.main()
```

### Resumen
- Pruebas unitarias son esenciales para asegurar la calidad del código.
- La biblioteca `unittest` de Python facilita el proceso de escritura y ejecución de pruebas.
- Las pruebas ayudan a identificar errores temprano en el desarrollo, mejorando la confiabilidad del software.