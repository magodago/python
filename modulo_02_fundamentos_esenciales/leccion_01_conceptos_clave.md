# Conceptos clave

## Objetivos
- Comprender los conceptos fundamentales de Python que son esenciales para cualquier programador.
- Familiarizarse con la sintaxis básica y la estructura de un programa en Python.

## Contenido
En esta lección, se explorarán los conceptos clave necesarios para comenzar a programar en Python. Se introducirá la sintaxis básica del lenguaje, incluyendo cómo escribir comentarios, declaraciones de variables y tipos de datos primitivos como enteros, flotantes y cadenas. Además, se explicará cómo estructurar un programa básico utilizando sentencias condicionales y bucles simples.

Los conceptos se presentarán a través de ejemplos prácticos que ilustran su uso en contextos reales, permitiendo al estudiante comprender no solo cómo escribir código, sino también por qué se escribe de esa manera.

## Ejercicio
Escribe un programa simple en Python que solicite al usuario su nombre y edad. El programa debe imprimir una frase personalizada que indique el nombre del usuario y cuántos días han pasado desde que nació hasta hoy (asumiendo 365 días por año).

```python
# Solicita al usuario que ingrese su nombre y edad
nombre = input("Por favor, introduce tu nombre: ")
edad = int(input("Ahora introduce tu edad: "))

# Calcula el número de días desde la fecha de nacimiento hasta hoy
dias_vividos = edad * 365

# Imprime una frase personalizada
print(f"Hola {nombre}, has vivido aproximadamente {dias_vividos} días.")
```

## Resumen
- Se presentaron los conceptos fundamentales de Python, incluyendo sintaxis básica y tipos de datos.
- Se ilustró cómo estructurar un programa básico utilizando entradas del usuario y cálculos simples.