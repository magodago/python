# Buenas practicas

- Comprender y aplicar las buenas prácticas de codificación según PEP 8.
- Implementar técnicas para mejorar la legibilidad del código.

Python es un lenguaje de programación versátil que se destaca por su sintaxis clara y concisa. Para maximizar la eficiencia y la comprensión del código, es crucial seguir ciertas buenas prácticas. Una de las guías más reconocidas en Python es PEP 8, que proporciona una serie de recomendaciones para el diseño y estilo del código. Algunas de estas recomendaciones incluyen el uso de espacios en blanco para mejorar la legibilidad, nombrar variables con minúsculas y underscores (snake_case), y limitar las líneas de código a 79 caracteres.

Para practicar, crea un script que implemente una función para calcular la suma de los primeros n números naturales. Asegúrate de seguir las recomendaciones de PEP 8 al escribir tu código. Por ejemplo:

```python
def suma_naturales(n):
    """
    Calcula la suma de los primeros n números naturales.
    
    :param n: Número natural
    :return: Suma de los primeros n números naturales
    """
    return (n * (n + 1)) // 2

# Prueba la función
print(suma_naturales(5))
```

- Asegurarse de seguir las recomendaciones de PEP 8.
- Escribir funciones claras y concisas.