# Revision

## Objetivos
- Comprender y aplicar técnicas avanzadas de programación en Python.
- Analizar y optimizar código existente utilizando métodos de programación funcional.

## Contenido
En esta lección, se revisará el uso de funciones lambda y comprensión de listas para mejorar la eficiencia del código. Se explorará cómo estas técnicas pueden ser utilizadas en situaciones donde el rendimiento es crítico. Además, se discutirá la importancia de la programación funcional en Python y cómo se puede aplicar para resolver problemas complejos de manera más concisa y legible.

Se analizarán ejemplos prácticos donde se compara el uso de funciones lambda con funciones normales, demostrando ventajas como la reducción del código y la mejora de la velocidad de ejecución. También se revisará cómo las listas comprehension pueden ser utilizadas para filtrar y transformar datos en una sola línea, lo que puede resultar en un código más limpio y eficiente.

## Ejercicio
Reescribe el siguiente código utilizando funciones lambda y comprensión de listas:

```python
# Código original
def squares(nums):
    result = []
    for num in nums:
        result.append(num * num)
    return result

numbers = [1, 2, 3, 4]
print(squares(numbers))
```

Utiliza funciones lambda y comprensión de listas para reescribir la función `squares` y mostrar los resultados.

## Resumen
- Las funciones lambda y las listas comprehension son herramientas poderosas que pueden mejorar el rendimiento del código.
- La programación funcional en Python puede ayudar a resolver problemas complejos de manera más concisa y legible.