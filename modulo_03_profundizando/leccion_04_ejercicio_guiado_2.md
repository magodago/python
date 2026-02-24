# Ejercicio guiado 2

- Entender la implementación de estructuras de datos avanzadas como árboles binarios de búsqueda.
- Implementar una función que permita insertar nodos en un árbol binario de búsqueda y verificar su correcto funcionamiento.

Para profundizar en el manejo de estructuras de datos, este ejercicio guiado se centrará en la implementación de un árbol binario de búsqueda (BST). Los árboles BST son útiles para realizar operaciones de búsqueda, inserción y eliminación con una complejidad promedio de O(log n), lo que los hace ideales para aplicaciones donde estas operaciones se realizan frecuentemente.

En esta lección, se proporcionará un esqueleto de código en Python que incluirá la definición de una clase `Node` y una clase `BinarySearchTree`. El alumno deberá completar la implementación del método `insert` en la clase `BinarySearchTree`, que permitirá insertar nodos en el árbol manteniendo su propiedad de BST. Además, se pedirá al estudiante que escriba una función auxiliar para verificar si un árbol es un BST válido.

### Ejercicio

**Ejercicio 1: Implementación del método `insert`**

Completar la implementación del método `insert` en la clase `BinarySearchTree`. Este método debe insertar un nuevo nodo en el árbol manteniendo las propiedades de un BST. Si el valor a insertar es menor que el valor del nodo actual, se debe insertar en el subárbol izquierdo; si es mayor, en el subárbol derecho.

```python
class Node:
    def __init__(self, key):
        self.left = None
        self.right = None
        self.val = key

class BinarySearchTree:
    def __init__(self):
        self.root = None
    
    # Completa este método
    def insert(self, key):
        if not self.root:
            self.root = Node(key)
        else:
            self._insert(self.root, key)

    def _insert(self, node, key):
        # Implementa la lógica aquí

# Prueba de inserción
bst = BinarySearchTree()
keys = [8, 3, 10, 1, 6, 14, 4, 7, 13]
for key in keys:
    bst.insert(key)

# Verificar si el árbol es un BST válido (ejercicio adicional)
def is_bst_valid(node):
    # Implementa la lógica aquí
```

**Ejercicio 2: Verificación de la estructura del BST**

Implementar una función `is_bst_valid` que verifique si el árbol creado sigue las propiedades de un BST. La función debe recorrer el árbol y verificar que cada nodo cumple con la condición de que todos los nodos en su subárbol izquierdo sean menores y todos los nodos en su subárbol derecho sean mayores.

### Resumen

- Se ha profundizado en la implementación de estructuras de datos avanzadas, específicamente árboles binarios de búsqueda.
- El estudiante ha aprendido a insertar nodos en un BST y a verificar si el árbol sigue las propiedades del BST.