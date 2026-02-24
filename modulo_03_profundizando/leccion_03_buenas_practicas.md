# Buenas practicas

- Comprender y aplicar las convenciones de codificación PEP8 para mejorar la legibilidad del código.
- Implementar buenas prácticas en el manejo de excepciones para hacer el código más robusto.

En esta lección profundizaremos en las mejores prácticas que se deben seguir al programar en Python. La calidad y claridad del código son fundamentales, no solo para facilitar su mantenimiento futuro, sino también para colaborar eficazmente con otros desarrolladores. Una de las herramientas más valiosas en este sentido es PEP8, un conjunto de convenciones que guían la escritura de código Python. Aprender a seguir estas recomendaciones permitirá que el código sea no solo funcional, sino también elegante y fácil de leer.

Para ejemplificar esto, consideremos el manejo de excepciones. Es crucial definir claramente qué excepciones se pueden lanzar en una función o método para que los usuarios del mismo puedan prever y tratar correctamente estos casos. Además, es importante capturar solo las excepciones específicas que se esperan, evitando usar `except Exception` como un "catch-all". Esto no solo mejora la robustez del código, sino también su rendimiento al evitar el costo de la evaluación innecesaria.

**Ejercicio:** Reescribe el siguiente fragmento de código siguiendo las convenciones PEP8 y mejorando el manejo de excepciones:
```python
def divide(a, b):
    return a / b
```

- Aplicar las convenciones de codificación PEP8.
- Mejorar la gestión de excepciones para hacer el código más robusto.