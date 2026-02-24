# Temas intermedios

- Comprender la utilización de funciones lambda y comprensión de listas para simplificar el código.
- Familiarizarse con el manejo avanzado de excepciones y su gestión en Python.

Las funciones lambda y la comprensión de listas son herramientas poderosas que permiten escribir código más conciso y eficiente. Las funciones lambda, también conocidas como funciones anónimas, son útiles para crear pequeñas funciones sin nombre. Por otro lado, la comprensión de listas ofrece una forma compacta de generar listas basadas en secuencias existentes o concreto cálculos.

Para ilustrar su uso, consideremos un ejemplo donde necesitamos filtrar y transformar una lista de números para obtener solo los pares mayores que 10. Podríamos hacerlo utilizando funciones lambda junto con comprensión de listas:

```python
numeros = [2, 5, 8, 9, 11, 13, 16, 17]
pares_mayores_10 = [x for x in map(lambda n: n * 2 if n % 2 == 0 and n > 10 else None, numeros) if x is not None]
print(pares_mayores_10)
```

Este código primero aplica una función lambda a cada elemento de la lista `numeros`, duplicando solo los números pares mayores que 10 y convirtiendo el resto en `None`. Luego, la comprensión de listas filtra estos valores, eliminando `None` para dejar solo los resultados deseados.

- Comprender cómo utilizar funciones lambda y comprensión de listas para optimizar el código.
- Aplicar correctamente el manejo avanzado de excepciones en situaciones específicas.