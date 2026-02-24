# Buenas practicas

## Objetivos
- Comprender y aplicar las mejores prácticas de codificación para mejorar la legibilidad y mantenibilidad del código.
- Aprender a utilizar documentación eficaz en los programas con comentarios y docstrings.

## Contenido
Las buenas prácticas son esenciales para escribir código Python que sea no solo funcional, sino también fácil de entender y mantener. Una práctica recomendada es el uso de nombres descriptivos para variables, funciones y clases, lo cual facilita la comprensión del propósito de cada elemento. Además, se recomienda utilizar espacios en blanco adecuadamente para mejorar la legibilidad del código. La documentación es otra parte crucial; los comentarios deben ser claros y útiles, mientras que las docstrings (documentación dentro de las funciones) son una buena práctica para explicar el propósito y los parámetros de cada función.

## Ejercicio
Escribe una función en Python que calcule la suma de dos números enteros. Asegúrate de:
- Usar un nombre descriptivo para la función.
- Agregar espacios adecuados alrededor de operadores y entre palabras.
- Incluir una docstring que explique qué hace la función, sus parámetros y su valor de retorno.

Ejemplo:

```python
def suma_numeros(a: int, b: int) -> int:
    """
    Calcula la suma de dos números enteros.

    Parámetros:
        a (int): El primer número.
        b (int): El segundo número.

    Retorna:
        int: La suma de los dos números.
    """
    return a + b
```

## Resumen
- Uso de nombres descriptivos y espacios en blanco para mejorar la legibilidad del código.
- Inclusión de docstrings para documentar funciones, explicando su propósito, parámetros y valor de retorno.