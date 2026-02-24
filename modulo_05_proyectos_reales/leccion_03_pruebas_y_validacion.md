# Pruebas y validacion

- Comprender la importancia de pruebas y validación en el desarrollo de proyectos Python.
- Implementar técnicas básicas de pruebas unitarias utilizando unittest.

Python es un lenguaje de programación versátil que se utiliza ampliamente en diversos campos, desde desarrollo web hasta ciencia de datos. Sin embargo, para garantizar que los programas funcionen correctamente y sean robustos, es crucial implementar pruebas y validaciones adecuadas. Las pruebas permiten identificar errores temprano en el proceso de desarrollo, lo cual reduce significativamente el tiempo de depuración y mejora la calidad del código.

Para esta lección, se utilizará la biblioteca `unittest` que viene incorporada con Python para implementar pruebas unitarias. Las pruebas unitarias son una forma de probar individualmente las partes más pequeñas de un programa (como funciones o métodos) para asegurarse de que funcionan como se espera.

### Ejercicio

Implementa un módulo `calculos.py` con funciones básicas de matemáticas, como suma y resta. Luego, escribe pruebas unitarias utilizando la biblioteca `unittest` en un archivo separado llamado `test_calculos.py`. Tu tarea es:

1. Definir las siguientes funciones en `calculos.py`:
   ```python
   def suma(a, b):
       return a + b

   def resta(a, b):
       return a - b
   ```

2. En el archivo `test_calculos.py`, utiliza `unittest` para escribir pruebas unitarias que verifiquen la funcionalidad de las funciones definidas en `calculos.py`. Por ejemplo:
   ```python
   import unittest
   from calculos import suma, resta

   class TestCalculos(unittest.TestCase):
       def test_suma(self):
           self.assertEqual(suma(1, 2), 3)

       def test_resta(self):
           self.assertEqual(resta(5, 3), 2)

   if __name__ == '__main__':
       unittest.main()
   ```

### Resumen

- Pruebas unitarias son esenciales para verificar que las partes individuales de un programa funcionen correctamente.
- La biblioteca `unittest` facilita la implementación de pruebas en Python, proporcionando una estructura y herramientas para asegurar el correcto comportamiento del código.