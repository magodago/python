# Temas intermedios

- Dominar la utilización de comprensión de listas para manipular datos.
- Implementar funciones recursivas y entender su uso adecuado.

Python nos permite realizar operaciones complejas con una sintaxis simple. Una de las características más poderosas es la comprensión de listas, que nos permite crear listas de manera concisa y eficiente. Por ejemplo:

```python
# Crear una lista de números pares hasta 10
pares = [x for x in range(11) if x % 2 == 0]
print(pares)
```

Además, las funciones recursivas son un concepto fundamental en programación que permite a una función llamar a sí misma para resolver problemas. Este método es especialmente útil cuando se trabaja con estructuras de datos jerárquicas o problemas que pueden dividirse en subproblemas similares.

Implementa una función recursiva que calcule el factorial de un número:

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

print(factorial(5))
```

Este ejercicio te permitirá practicar tanto la comprensión de listas como la implementación de funciones recursivas.

- Comprender y utilizar eficientemente la comprensión de listas.
- Implementar y entender el uso de funciones recursivas en Python.