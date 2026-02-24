# Revision

## Objetivos
- Comprender y aplicar técnicas avanzadas de programación con Python.
- Analizar y optimizar código existente utilizando patrones de diseño.

## Contenido
En esta lección revisaremos técnicas avanzadas en Python, enfocándonos en la optimización del código y el uso efectivo de patrones de diseño. Veremos cómo mejorar el rendimiento y la legibilidad del código a través de la utilización de decoradores, métodos de clase estáticos y propiedades de clase. Además, exploraremos cómo implementar patrones de diseño como Singleton y Factory para resolver problemas comunes en la programación orientada a objetos.

## Ejercicio
Dado el siguiente código:

```python
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre

def saludar(persona):
    return f"Hola, {persona.nombre}"

personas = [Persona("Juan"), Persona("María"), Persona("Pedro")]

# Implemente una función que utilice un decorador para contar cuántas veces se llama a la función `saludar`.
```

Implemente el código necesario para cumplir con este requisito y luego optimice la función `saludar` utilizando métodos de clase estáticos o propiedades de clase.

## Resumen
- Se revisaron técnicas avanzadas como decoradores, métodos de clase estáticos y propiedades de clase.
- Se exploró cómo implementar patrones de diseño para mejorar el código.