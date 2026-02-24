# Ejercicio guiado 2

## Objetivos
- Familiarizarse con la manipulación de listas y diccionarios.
- Aprender a utilizar funciones para procesar datos complejos.

## Contenido
En esta lección profundizaremos en el manejo de listas y diccionarios, dos estructuras de datos fundamentales en Python. Veremos cómo realizar operaciones más avanzadas con estas estructuras, como la búsqueda, inserción y eliminación de elementos, así como la manipulación de subconjuntos y sublistas. Además, aprenderemos a definir funciones que puedan procesar estos tipos de datos de manera eficiente.

## Ejercicio
Dado un diccionario `libros` donde las claves son los títulos de libros y los valores son listas con información sobre cada libro (título, autor, año de publicación), escribe una función `filtrar_libros_por_autor` que tome como parámetros el diccionario `libros` y un autor específico. La función debe devolver una lista de títulos de libros escritos por ese autor.

```python
def filtrar_libros_por_autor(libros, autor):
    # Inicializa una lista para almacenar los títulos del autor
    titulos_del_autor = []
    
    # Itera a través de cada clave (título) en el diccionario `libros`
    for titulo in libros.keys():
        # Verifica si el autor está en la lista de autores asociada con el título actual
        if autor in libros[titulo]:
            # Si es así, agrega el título a la lista
            titulos_del_autor.append(titulo)
    
    return titulos_del_autor

# Ejemplo de uso
libros = {
    "El Gran Gatsby": ["F. Scott Fitzgerald", 1925],
    "Cien años de soledad": ["Gabriel García Márquez", 1967],
    "Orgullo y prejuicio": ["Jane Austen", 1813]
}

print(filtrar_libros_por_autor(libros, "F. Scott Fitzgerald"))
```

## Resumen
- Se profundiza en el manejo de listas y diccionarios.
- Se aprende a definir funciones para procesar datos complejos.
- Se desarrolla una función que filtra libros por autor utilizando un diccionario.