# Ejercicio guiado 2

## Objetivos
- Aprender a utilizar la biblioteca `collections` para trabajar con estructuras de datos avanzadas.
- Familiarizarse con el uso de `deque`, una estructura de datos doblemente encolada, y sus aplicaciones prácticas.

## Contenido
En esta lección profundizaremos en la biblioteca `collections` de Python, que proporciona varias clases de colecciones adicionales más allá de las implementadas por defecto. Una de estas clases es `deque`, una estructura de datos doblemente encolada (double-ended queue) que permite realizar operaciones de inserción y eliminación tanto en el extremo izquierdo como en el derecho con eficiencia.

`deque` se utiliza comúnmente cuando se necesita un almacén de elementos donde los elementos se añaden o remueven desde ambos extremos. Este tipo de estructura es ideal para implementar tareas como la gestión de colas, buffers y procesamiento de datos en tiempo real.

## Ejercicio
Implementa una función que simule el juego del ahorcado utilizando `deque` para almacenar las letras ingresadas por el usuario. La función debe permitir al usuario ingresar una letra cada vez, verificar si la letra está en la palabra secreta y actualizar la representación de la palabra con guiones bajos y letras reveladas. Utiliza `deque` para gestionar una pila temporal de letras incorrectas.

```python
from collections import deque

def ahorcado(palabra_secreta):
    # Inicializar el juego
    letras_correctas = set()
    letras_incorrectas = deque(maxlen=5)  # Máximo 5 intentos
    palabra_mostrada = ['_'] * len(palabra_secreta)
    
    while '_' in palabra_mostrada and len(letras_incorrectas) < 6:
        print(' '.join(palabra_mostrada))
        letra = input("Ingresa una letra: ").lower()
        
        if letra in letras_incorrectas or letra in letras_correctas:
            print("Letra ya utilizada. Inténtalo de nuevo.")
            continue
        
        if letra in palabra_secreta:
            for i, char in enumerate(palabra_secreta):
                if char == letra:
                    letras_correctas.add(letra)
                    palabra_mostrada[i] = letra
        else:
            letras_incorrectas.append(letra)
    
    print(' '.join(palabra_mostrada))
    if '_' not in palabra_mostrada:
        print("¡Ganaste!")
    else:
        print(f"Perdiste. La palabra era: {palabra_secreta}")

# Ejemplo de uso
ahorcado("python")
```

## Resumen
- `deque` es una estructura de datos doblemente encolada que permite operaciones eficientes desde ambos extremos.
- Se puede utilizar para implementar juegos como el ahorcado, gestionando las letras ingresadas y incorrectas.