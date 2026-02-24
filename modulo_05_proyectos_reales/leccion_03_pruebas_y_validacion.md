# Pruebas y validacion

- Comprender la importancia de pruebas y validación en el desarrollo de software.
- Implementar técnicas básicas de pruebas unitarias utilizando la biblioteca `unittest` de Python.

Las pruebas y la validación son fundamentales en el desarrollo de software para asegurar que las funciones se comporten como se espera. En esta lección, aprenderás a utilizar la biblioteca `unittest`, una parte integral del estándar de Python, para escribir y ejecutar pruebas unitarias. Estas pruebas ayudan a detectar errores temprano en el proceso de desarrollo, lo que facilita la corrección de defectos antes de que se propaguen al código final.

Para empezar, crea un archivo `test_calculos.py` con las siguientes líneas:

```python
import unittest

class TestCalculos(unittest.TestCase):
    
    def test_suma(self):
        from calculos import suma
        self.assertEqual(suma(1, 2), 3)
        
    def test_resta(self):
        from calculos import resta
        self.assertEqual(resta(5, 3), 2)

if __name__ == '__main__':
    unittest.main()
```

Este código define una clase de prueba `TestCalculos` que incluye dos métodos de prueba: `test_suma` y `test_resta`. Estos métodos utilizan el framework de pruebas `unittest` para verificar que las funciones `suma` y `resta`, importadas desde un módulo llamado `calculos`, funcionen correctamente.

- Implementar pruebas unitarias con la biblioteca `unittest`.
- Utilizar técnicas básicas de validación en Python.