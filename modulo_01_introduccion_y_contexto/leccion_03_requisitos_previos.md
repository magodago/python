# Requisitos previos

- Comprender los requisitos previos necesarios antes de comenzar a aprender Python.
- Identificar las habilidades y conocimientos básicos que facilitan la adquisición del lenguaje de programación.

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Para comenzar a aprender Python, los estudiantes deben tener ciertos requisitos previos que les ayuden a comprender y manejar el lenguaje más fácilmente. Estos incluyen conocimientos básicos de matemáticas, una comprensión elemental del concepto de programación (como variables, estructuras de datos simples) y la capacidad para leer y escribir en inglés, ya que la documentación oficial de Python está principalmente en inglés.

Es recomendable que los estudiantes tengan experiencia con otros lenguajes de programación o al menos con el uso de un entorno de desarrollo integrado (IDE), como PyCharm o Visual Studio Code. Además, tener una comprensión básica de conceptos matemáticos y lógicos facilitará la comprensión de ciertas funcionalidades y estructuras en Python.

### Ejercicio
Escriba un programa simple que solicite al usuario ingresar su nombre y edad, luego imprima un mensaje personalizado. El programa debe validar que la entrada de edad sea un número entero.

```python
nombre = input("Por favor, ingresa tu nombre: ")
edad = input("Ahora, ingresa tu edad: ")

try:
    edad = int(edad)
    print(f"Bienvenido {nombre}! Tienes {edad} años.")
except ValueError:
    print("Error: La edad debe ser un número entero.")
```

- Requisitos previos recomendados para aprender Python.
- Ejercicio práctico para evaluar la comprensión inicial.