# Enunciado del proyecto

## Objetivos
- Comprender y definir claramente los requisitos del proyecto final.
- Desarrollar habilidades para planificar y estructurar un proyecto de Python.

## Contenido
En esta lección, se presentará el enunciado del proyecto final del curso de Python. El objetivo es que los estudiantes comprendan completamente la tarea a realizar y puedan comenzar a planificar su trabajo. El proyecto consiste en desarrollar una aplicación de línea de comandos (CLI) que permita al usuario interactuar con un sistema de gestión de tareas. La aplicación debe incluir funcionalidades para agregar, listar, marcar como completadas y eliminar tareas.

El enunciado detalla las características básicas del proyecto, así como las expectativas sobre la estructura del código y el uso de buenas prácticas de programación. Se espera que los estudiantes utilicen conceptos avanzados estudiados durante el curso, como funciones, listas, diccionarios y manejo de excepciones.

## Ejercicio
Desarrolla un esbozo básico para la aplicación CLI de gestión de tareas mencionada en el enunciado. Incluye las siguientes funcionalidades:

1. Agregar una tarea.
2. Listar todas las tareas pendientes.
3. Marcar una tarea como completada.
4. Eliminar una tarea.

Puedes utilizar la siguiente estructura inicial para tu aplicación:

```python
def agregar_tarea(tareas, tarea_nueva):
    # Implementa esta función

def listar_tareas(tareas):
    # Implementa esta función

def marcar_como_completada(tareas, indice):
    # Implementa esta función

def eliminar_tarea(tareas, indice):
    # Implementa esta función

if __name__ == "__main__":
    tareas = []
    while True:
        print("1. Agregar tarea")
        print("2. Listar tareas")
        print("3. Marcar como completada")
        print("4. Eliminar tarea")
        print("5. Salir")
        
        opcion = input("Elige una opción: ")
        
        if opcion == "1":
            # Llama a la función agregar_tarea
        elif opcion == "2":
            # Llama a la función listar_tareas
        elif opcion == "3":
            # Llama a la función marcar_como_completada
        elif opcion == "4":
            # Llama a la función eliminar_tarea
        elif opcion == "5":
            break
```

## Resumen
- El proyecto final implica desarrollar una aplicación CLI para gestionar tareas.
- Los estudiantes deben planificar y estructurar su trabajo siguiendo el enunciado proporcionado.
- Se recomienda que los estudiantes comiencen con un esbozo básico de la aplicación.