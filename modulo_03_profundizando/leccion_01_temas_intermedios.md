# Temas intermedios

## Objetivos
- Comprender la utilización de las excepciones y manejo de errores en Python.
- Familiarizarse con la programación orientada a objetos (POO) avanzada.

## Contenido
En esta lección, profundizaremos en el manejo de excepciones y la implementación de programación orientada a objetos (POO) en Python. Las excepciones son un mecanismo crucial para manejar errores de manera eficiente en el código. Podremos aprender cómo definir nuestras propias excepciones y utilizarlas para mejorar la robustez del software. Además, se explorarán conceptos avanzados de POO como herencia múltiple, polimorfismo y encapsulamiento, con ejemplos prácticos.

## Ejercicio
Escribe un programa que simule una calculadora básica (suma, resta, multiplicación y división) utilizando clases y métodos. Implementa la lógica de manejo de excepciones para tratar divisiones por cero y entradas inválidas.

```python
class Calculadora:
    def __init__(self):
        pass

    def suma(self, a, b):
        return a + b

    def resta(self, a, b):
        return a - b

    def multiplicacion(self, a, b):
        return a * b

    def division(self, a, b):
        try:
            return a / b
        except ZeroDivisionError:
            print("No se puede dividir por cero.")
```

## Resumen
- Se aprendió a definir y utilizar excepciones personalizadas en Python.
- Se profundizó en la programación orientada a objetos, cubriendo temas como herencia múltiple y manejo de errores.