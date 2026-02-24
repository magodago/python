# Ejercicio guiado 2

## Objetivos
- Familiarizar al estudiante con la manipulación de listas y diccionarios en Python.
- Desarrollar habilidades para la resolución de problemas a través del uso de bucles anidados.

## Contenido
En esta lección, profundizaremos en el manejo de estructuras de datos complejas como listas y diccionarios. Veremos cómo combinar estas estructuras con bucles para realizar operaciones más avanzadas. Por ejemplo, podrás aprender a recorrer una lista de diccionarios, manipular los valores dentro de estos y aplicar diferentes operaciones según ciertas condiciones.

Para ilustrar esto, veremos un caso práctico donde se manejará una base de datos simple de productos en un inventario. Cada producto estará representado por un diccionario con información como el nombre, precio y stock disponible. El objetivo será calcular el valor total del inventario y actualizar el stock según la venta de ciertos productos.

## Ejercicio
Dado el siguiente código inicial:

```python
inventario = [
    {"nombre": "Camisa", "precio": 50, "stock": 10},
    {"nombre": "Pantalon", "precio": 80, "stock": 5},
    {"nombre": "Zapatos", "precio": 120, "stock": 3}
]
```

Escribe una función `calcular_valor_total(inventario)` que devuelva el valor total del inventario. Luego, implementa una función `actualizar_stock(inventario, producto_vendido, cantidad_vendida)` que actualice el stock de los productos vendidos.

Finalmente, utiliza estas funciones para calcular el valor total del inventario y actualizar el stock después de vender 2 camisas, 1 pantalón y 3 zapatos.

## Resumen
- Se aprendió a manipular listas y diccionarios en Python.
- Se practicó la resolución de problemas utilizando bucles anidados para recorrer estructuras de datos complejas.