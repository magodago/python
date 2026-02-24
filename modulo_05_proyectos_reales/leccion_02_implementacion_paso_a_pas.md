# Implementacion paso a paso

- Comprender cómo estructurar un proyecto real en Python.
- Implementar una solución práctica utilizando bucles y funciones.

Para esta lección, vamos a desarrollar un proyecto que consiste en la creación de un programa simple para administrar tareas pendientes. Este programa permitirá al usuario agregar, eliminar y listar tareas. Utilizaremos listas y funciones para manejar las tareas y bucles para interactuar con el usuario.

El programa se dividirá en varias partes:

1. Definir una función `agregar_tarea` que permita al usuario ingresar nuevas tareas.
2. Implementar una función `listar_tareas` que muestre todas las tareas actuales.
3. Crear una función `eliminar_tarea` para permitir la eliminación de tareas específicas.
4. Utilizar un bucle principal para interactuar con el usuario y manejar sus elecciones.

El código básico podría verse así:

```python
tareas = []

def agregar_tarea():
    tarea_nueva = input("Ingresa una nueva tarea: ")
    tareas.append(tarea_nueva)
    print(f"Tarea '{tarea_nueva}' agregada.")

def listar_tareas():
    if not tareas:
        print("No hay tareas pendientes.")
    else:
        for i, tarea in enumerate(tareas):
            print(f"{i + 1}. {tarea}")

def eliminar_tarea():
    listar_tareas()
    indice = int(input("Ingresa el número de la tarea a eliminar: ")) - 1
    if 0 <= indice < len(tareas):
        eliminada = tareas.pop(indice)
        print(f"Tarea '{eliminada}' eliminada.")
    else:
        print("Índice inválido.")

def main():
    while True:
        print("\nMenú:")
        print("1. Agregar tarea")
        print("2. Listar tareas")
        print("3. Eliminar tarea")
        print("4. Salir")
        opcion = input("Elige una opción: ")

        if opcion == "1":
            agregar_tarea()
        elif opcion == "2":
            listar_tareas()
        elif opcion == "3":
            eliminar_tarea()
        elif opcion == "4":
            break
        else:
            print("Opción inválida. Inténtalo de nuevo.")

if __name__ == "__main__":
    main()
```

Prueba este código y realiza las modificaciones necesarias para mejorar la funcionalidad del programa, como agregar validación de entrada o manejo de errores.

- Comprender la estructura básica de un proyecto en Python.
- Utilizar funciones y bucles para interactuar con el usuario.