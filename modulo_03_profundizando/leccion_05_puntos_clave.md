# Puntos clave

- Comprender la implementación de decoradores avanzados en Python.
- Aplicar patrones de diseño con decoradores para mejorar la reutilización y modularidad del código.

Python es una de las lenguas más versátiles y poderosas, y uno de sus aspectos más atractivos son los decoradores. Estos permiten modificar funcionalidades existentes sin alterar su estructura original, lo que facilita la extensión y mantenimiento del software. Los decoradores avanzados pueden manejar parámetros, permitir múltiples llamadas y aplicarse a funciones, métodos de clases o incluso a otras funciones decoradoras.

Para ilustrar esto, vamos a crear un decorador que mide el tiempo de ejecución de una función. Este decorador no solo nos ayudará a evaluar la eficiencia del código, sino que también puede servir como base para otros decoradores más complejos. El ejercicio consiste en implementar este decorador y luego aplicarlo a diferentes funciones matemáticas.

## Ejercicio
Implementa un decorador llamado `tiempo_ejecucion` que muestre el tiempo de ejecución de una función. Luego, aplica este decorador a las siguientes funciones:
- Una función que calcule la suma de los primeros 100 números naturales.
- Otra función que genere y devuelva una lista con los primeros 50 números primos.

## Resumen
- Los decoradores avanzados permiten modificar funcionalidades sin alterar el código original.
- Se puede crear un decorador que mida el tiempo de ejecución para evaluar la eficiencia del código.