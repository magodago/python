# Ejercicio guiado 2

## Objetivos
- Familiarizar al estudiante con la manipulación de archivos en Python.
- Introducir el uso de la biblioteca `csv` para leer y escribir datos.

## Contenido
En esta lección profundizaremos en la manipulación de archivos utilizando Python. Veremos cómo abrir, leer y escribir archivos utilizando métodos estándar del lenguaje. Además, introduciremos el uso de la biblioteca `csv`, que facilita trabajar con archivos CSV (Comma-Separated Values), un formato común para intercambiar datos entre programas. A través de ejemplos prácticos, aprenderemos a leer y escribir datos en archivos CSV utilizando funciones como `read_csv` y `write_csv`.

## Ejercicio
Dado el siguiente código base:

```python
import csv

def cargar_datos(ruta_archivo):
    with open(ruta_archivo, mode='r', newline='') as archivo:
        lector = csv.reader(archivo)
        datos = [fila for fila in lector]
    return datos

def guardar_datos(ruta_archivo, datos):
    with open(ruta_archivo, mode='w', newline='') as archivo:
        escritor = csv.writer(archivo)
        escritor.writerows(datos)

# Ejemplo de uso
ruta = 'datos.csv'
datos = cargar_datos(ruta)
print("Datos cargados:", datos)

nuevo_dato = ['Nombre', 'Edad', 'Ciudad']
guardar_datos(ruta, [nuevo_dato] + datos)
```

1. Corrige el código para que funcione correctamente.
2. Agrega una función `agregar_dato` que permita agregar un nuevo registro a la lista de datos y guarde estos cambios en el archivo CSV.
3. Prueba tu implementación agregando un nuevo dato y verifica si se ha guardado correctamente.

## Resumen
- Se aprendió cómo manipular archivos utilizando métodos estándar de Python.
- Se introdujo el uso de la biblioteca `csv` para trabajar con archivos CSV.
- Se realizó un ejercicio práctico que involucró cargar, guardar y agregar datos en archivos CSV.