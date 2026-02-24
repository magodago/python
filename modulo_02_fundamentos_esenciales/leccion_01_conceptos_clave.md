# Conceptos clave

## Objetivos
- Comprender los conceptos básicos de Python.
- Familiarizarse con la sintaxis y estructura fundamental del lenguaje.

## Contenido
En esta lección, se explorarán los fundamentos esenciales de Python. Se tratará el entorno de desarrollo integrado (IDE) como PyCharm o Jupyter Notebook, que proporcionan un espacio para escribir y ejecutar código. Se explicará la sintaxis básica, incluyendo cómo declarar variables, tipos de datos primitivos como enteros, flotantes y cadenas, así como operadores aritméticos y comparativos. También se presentarán las estructuras condicionales básicas, como `if`, `elif` y `else`, y las estructuras iterativas con bucles `for` e `while`.

## Ejercicio
Escribe un programa en Python que solicite al usuario su nombre y edad, muestre un mensaje de bienvenida personalizado, y luego calcule y muestre la edad del usuario en el año 2050.

```python
nombre = input("¿Cuál es tu nombre? ")
edad = int(input("¿Cuántos años tienes? "))

print(f"¡Bienvenido/a {nombre}!")

año_actual = 2023
años_futuro = 2050 - año_actual

edad_2050 = edad + años_futuro
print(f"En el año 2050 tendrás {edad_2050} años.")
```

## Resumen
- Entorno de desarrollo integrado (IDE) para Python.
- Sintaxis básica, incluyendo variables y tipos de datos primitivos.
- Estructuras condicionales y iterativas.