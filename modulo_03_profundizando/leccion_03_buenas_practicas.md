# Buenas practicas

## Objetivos
- Comprender y aplicar las mejores prácticas para la escritura de código Python.
- Identificar y corregir errores comunes basados en buenas prácticas.

## Contenido
Las buenas prácticas son fundamentales para escribir código Python limpio, eficiente y fácil de mantener. Algunas de estas prácticas incluyen el uso de nombres descriptivos para variables y funciones, la documentación adecuada con comentarios y docstrings, y la correcta indentación y estructura del código. Además, es crucial utilizar las bibliotecas y módulos estándar de Python de manera eficiente, evitando redundancias y optimizando el rendimiento.

Un aspecto importante son los estándares de estilo PEP 8, que proporcionan guías detalladas sobre cómo formatear el código para mejorar su legibilidad. Algunos puntos clave incluyen la longitud máxima de las líneas (79 caracteres), la utilización del doble espacio después de comas y paréntesis, y la preferencia por el uso de `snake_case` para nombres de variables y funciones.

## Ejercicio
Revisa el siguiente código y aplica las mejores prácticas descritas en esta lección:

```python
def calcular_promedio(numeros):
    suma = 0
    for n in numeros:
        suma += n
    promedio = suma / len(numeros)
    return promedio

numeros = [1, 2, 3, 4, 5]
print("El promedio es:", calcular_promedio(numeros))
```

Corrige los errores y mejora el código siguiendo las recomendaciones de PEP 8.

## Resumen
- Aplicar PEP 8 para mejorar la legibilidad del código.
- Utilizar nombres descriptivos y comentarios para documentar claramente el código.