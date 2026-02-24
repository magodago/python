# Conceptos clave

## Objetivos
- Comprender los conceptos fundamentales de Python.
- Familiarizarse con la sintaxis básica y las características esenciales del lenguaje.

## Contenido
Python es un lenguaje de programación interpretado, de alto nivel y fácil de aprender. Su sintaxis clara y concisa lo hace ideal para principiantes en programación. Las variables en Python son dinámicas, lo que significa que no se necesita declarar el tipo de dato al asignar un valor a una variable; Python determina el tipo automáticamente.

Las estructuras de control básicas incluyen if-elif-else y bucles for y while, permitiendo la ejecución condicional del código y la iteración sobre secuencias. Las funciones en Python son objetos de primera clase, lo que significa que pueden ser asignadas a variables, pasadas como argumentos a otras funciones y retornadas como valores.

## Ejercicio
Escribe un programa simple que solicite al usuario su nombre y edad, luego imprima un mensaje personalizado. Utiliza una función para pedir el nombre y otra para calcular si la persona es mayor de edad (21 años o más).

```python
def obtener_nombre():
    return input("Por favor, introduce tu nombre: ")

def es_mayor_de_edad(edad):
    return edad >= 21

nombre = obtener_nombre()
edad = int(input("Introduce tu edad: "))

if es_mayor_de_edad(edad):
    print(f"¡{nombre}, eres mayor de edad!")
else:
    print(f"Lo siento, {nombre}. Aún no eres mayor de edad.")
```

## Resumen
- Python es un lenguaje de programación interpretado y de alto nivel.
- Las variables en Python son dinámicas y la sintaxis es clara.
- Las funciones son objetos de primera clase y se pueden utilizar como cualquier otro objeto.