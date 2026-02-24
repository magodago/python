# Buenas practicas

## Objetivos
- Comprender y aplicar las mejores prácticas de codificación para mejorar la legibilidad y mantenibilidad del código Python.
- Aprender a documentar eficazmente el código utilizando comentarios y docstrings.

## Contenido
Las mejores prácticas en programación con Python son fundamentales para escribir código que sea fácil de leer, mantener y escalar. Una de las primeras reglas es usar nombres descriptivos para variables, funciones y clases, lo cual facilita entender el propósito de cada elemento del programa sin necesidad de consultar su definición. Además, es recomendable seguir la convención PEP 8, que establece estándares de codificación para Python, como la indentación uniforme con cuatro espacios y el uso de sangría para separar bloques de código.

La documentación es crucial en cualquier proyecto de software. En Python, se recomienda usar docstrings para describir claramente lo que hace cada función o método. Estas docstrings deben ser concisas pero informativas, incluyendo parámetros de entrada, valor de retorno y posibles excepciones. Además, el uso de comentarios en código auxiliar o no es necesario puede ayudar a explicar decisiones de diseño complejas.

## Ejercicio
Escribe una función en Python que calcule el área de un círculo dado su radio. Utiliza una docstring para describir la función y asegúrate de seguir las mejores prácticas de codificación, como nombrar correctamente las variables y usar sangría uniforme.

```python
def area_circulo(radio):
    """
    Calcula el área de un círculo dado su radio.

    Parámetros:
        radio (float): El radio del círculo.

    Devuelve:
        float: El área del círculo.
    """
    from math import pi
    return pi * radio ** 2

print(area_circulo(5))
```

## Resumen
- Utilizar nombres descriptivos para variables y funciones.
- Seguir la convención PEP 8 para un código uniforme.
- Documentar eficazmente el código con docstrings.