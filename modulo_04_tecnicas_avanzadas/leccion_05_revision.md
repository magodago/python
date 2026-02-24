# Revision

## Objetivos
- Analizar y optimizar código existente utilizando técnicas avanzadas de Python.
- Introducir conceptos de programación funcional y su aplicación práctica.

## Contenido
En esta lección de tecnicas avanzadas, revisaremos el uso de decoradores en Python para mejorar la legibilidad y reutilización del código. Los decoradores permiten modificar o extender las funcionalidades de funciones o métodos sin alterar su estructura original. Además, introduciremos conceptos básicos de programación funcional como map(), filter() y reduce(), que nos ayudarán a escribir código más conciso y eficiente.

## Ejercicio
Reescribe la función siguiente para calcular el factorial de un número utilizando una función recursiva y luego optimízala usando un decorador que limite el número máximo de llamadas recursivas. Posteriormente, implementa programación funcional utilizando `reduce()` para reemplazar la versión recursiva.

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
```

## Resumen
- Decoradores en Python permiten modificar funciones de manera dinámica.
- La programación funcional puede mejorar la eficiencia y claridad del código mediante métodos como `map()`, `filter()` y `reduce()`.