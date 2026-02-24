# Conceptos clave

## Objetivos
- Comprender los conceptos básicos de Python.
- Familiarizarse con la sintaxis y estructura fundamental del lenguaje.

## Contenido
En esta lección se presentarán los fundamentos esenciales de Python, un lenguaje de programación de alto nivel conocido por su simplicidad y claridad. Los conceptos clave incluyen variables y tipos de datos, control de flujo con estructuras condicionales y bucles, y la utilización de funciones para organizar el código. Estos elementos forman la base sobre la cual se construirán habilidades más avanzadas en futuras lecciones.

Las variables y los tipos de datos son fundamentales ya que permiten almacenar y manipular información. Python soporta diversos tipos, como enteros (int), flotantes (float) y cadenas de texto (str). Las estructuras condicionales, como `if` y `elif`, permiten ejecutar código basado en condiciones lógicas, mientras que los bucles (`for` y `while`) se utilizan para repetir bloques de código. Finalmente, las funciones son un mecanismo para encapsular y reutilizar código.

## Ejercicio
Escribe un programa simple en Python que solicite al usuario su nombre y edad. Luego, imprime un mensaje saludándolo por su nombre e indicando cuántos años cumplirá el próximo año.

```python
# Solicitar al usuario su nombre y edad
nombre = input("¿Cuál es tu nombre? ")
edad = int(input("¿Cuál es tu edad? "))

# Calcular la edad del próximo año
edad_siguiente_anio = edad + 1

# Imprimir el saludo personalizado
print(f"Hola, {nombre}! El próximo año cumplirás {edad_siguiente_anio} años.")
```

## Resumen
- Las variables y tipos de datos son esenciales para almacenar información.
- Estructuras condicionales y bucles permiten controlar el flujo del programa.
- Las funciones ayudan a organizar y reutilizar código.