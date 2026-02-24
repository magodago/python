# Proyecto practico 1

## Objetivos
- Desarrollar una aplicación que permita a los usuarios crear y gestionar un calendario personal.
- Implementar la integración de múltiples formatos de archivos para la importación y exportación de eventos.

## Contenido
En esta lección, se enfocará en el desarrollo de una aplicación de línea de comandos (CLI) que permita a los usuarios crear, modificar y eliminar eventos en un calendario personal. La aplicación también incluirá la funcionalidad para importar y exportar eventos desde y hacia archivos CSV y JSON.

Para lograr esto, se utilizarán técnicas avanzadas como la gestión de excepciones, el uso de clases para estructurar la lógica del programa, y la manipulación de archivos. Se discutirá cómo manejar diferentes formatos de datos y convertirlos entre ellos utilizando librerías como `csv` y `json`.

Además, se explorará cómo implementar un menú interactivo que permita a los usuarios navegar fácilmente por las funcionalidades del programa.

## Ejercicio
Implemente una función que permita al usuario exportar la lista de eventos actual en el calendario personal a un archivo CSV. La función debe recibir como argumento el nombre del archivo y escribir en él los datos de cada evento en formato CSV, incluyendo el título, la fecha y la hora.

```python
def exportar_a_csv(nombre_archivo: str):
    # Implemente aquí su código
```

## Resumen
- Se desarrollará una aplicación CLI para gestionar un calendario personal.
- La implementación incluirá la funcionalidad de importación y exportación de eventos en formato CSV y JSON.