# Buenas practicas

## Objetivos
- Comprender y aplicar las mejores prácticas de codificación en Python.
- Mejorar la legibilidad y mantenibilidad del código mediante la aplicación de convenciones.

## Contenido
En esta lección, profundizaremos en las buenas prácticas para escribir código Python eficiente y legible. El uso consistente de estas prácticas no solo facilita el trabajo en equipo sino que también reduce errores y mejora la calidad del software. Entre los aspectos clave se encuentran la utilización de nombres descriptivos, la indentación adecuada, la documentación clara y la gestión eficiente de excepciones.

Una práctica fundamental es utilizar nombres de variables y funciones descriptivos para facilitar su comprensión. Por ejemplo, en lugar de `x`, se recomienda usar `numero_de_productos` o `precio_total`. Además, el uso de espacios alrededor de operadores aritméticos y lógicos (por ejemplo, `a = b + c`) mejora la legibilidad del código.

## Ejercicio
Escribe una función en Python que calcule el área de un triángulo dado su base y altura. La función debe llamarse `calcular_area_triangulo` y recibir dos parámetros: `base` y `altura`. Adicionalmente, agrega comentarios descriptivos para cada línea del código.

```python
def calcular_area_triangulo(base, altura):
    """
    Calcula el área de un triángulo.
    
    Parámetros:
    base (float): La longitud de la base del triángulo.
    altura (float): La altura del triángulo.
    
    Devuelve:
    float: El área calculada.
    """
    # Calcular el área usando la fórmula A = (base * altura) / 2
    area = (base * altura) / 2
    return area
```

## Resumen
- Utilizar nombres de variables y funciones descriptivos para mejorar la legibilidad del código.
- Aplicar indentación adecuada y uso de espacios alrededor de operadores para facilitar la lectura.