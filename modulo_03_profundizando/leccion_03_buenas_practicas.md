# Buenas practicas

- Comprender y aplicar las buenas prácticas de codificación para mejorar la legibilidad y mantenibilidad del código.
- Implementar estándares de estilo PEP 8 y otras convenciones comunes en proyectos Python.

Las buenas prácticas son fundamentales para escribir código que sea no solo funcional, sino también fácil de leer y mantener. En Python, una de las mejores guías es la documentación oficial PEP 8, que proporciona recomendaciones sobre cómo estructurar el código, nombrar variables y funciones, y formatear el texto. Adherirse a estas convenciones no solo mejora la calidad del código, sino que también facilita su colaboración en proyectos de equipo.

Para ilustrar esto, vamos a realizar un ejercicio práctico. Se te proporcionará un fragmento de código que realiza una operación matemática simple. Tu tarea es refactorizar este código siguiendo las recomendaciones de PEP 8 y otras convenciones comunes. El objetivo es hacer el código más claro y legible.

```python
# Código original
def calculo(x, y):
    z = (x * 2) + (y / 3)
    return z

print(calculo(4, 6))
```

**Refactorizado:**

```python
# Código refactorizado
def calculo(x: float, y: float) -> float:
    """Realiza una operación matemática simple.

    Args:
        x (float): Primer valor.
        y (float): Segundo valor.

    Returns:
        float: Resultado de la operación.
    """
    z = (x * 2) + (y / 3)
    return z

print(calculo(4, 6))
```

- Adherirse a las convenciones de estilo PEP 8.
- Documentar claramente el código con comentarios y docstrings.