# Puntos clave

- Comprender y aplicar la optimización de código mediante la utilización de listas comprensivas y funciones lambda.
- Implementar eficientemente estructuras de datos complejas como diccionarios y conjuntos para resolver problemas específicos.

Python nos permite optimizar nuestro código a través del uso de listas comprensivas, que son una forma concisa y eficiente de crear listas. Por ejemplo, en lugar de usar un bucle `for` para generar una lista de números pares hasta 10, podríamos escribir:

```python
pares = [x for x in range(2, 11, 2)]
```

Además, las funciones lambda son útiles cuando necesitamos definir pequeñas funciones anónimas en el momento. Por ejemplo, para ordenar una lista de tuplas por su segundo elemento podríamos usar:

```python
tuplas = [("a", 3), ("b", 1), ("c", 2)]
tuplas_ordenadas = sorted(tuplas, key=lambda x: x[1])
```

Para practicar, implementa una función que use listas comprensivas para generar un diccionario donde las claves sean los números del 1 al 10 y sus valores sean el cuadrado de cada número.

## Resumen
- Listas comprensivas permiten crear listas de forma concisa y eficiente.
- Funciones lambda son útiles para definir funciones anónimas en el momento, especialmente en combinación con métodos como `sorted`.