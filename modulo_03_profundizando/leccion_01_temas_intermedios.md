# Temas intermedios

Objetivos
- Comprender la utilización de decoradores para mejorar y reutilizar código.
- Aprender a trabajar con módulos y paquetes externos en Python.

Contenido
En esta lección profundizaremos en temas intermedios de Python, enfocándonos en dos aspectos cruciales: los decoradores y la gestión de módulos y paquetes. Los decoradores son una característica poderosa que permite modificar o extender las funcionalidades de otras funciones sin alterar su estructura original. Esto es especialmente útil para aplicaciones como manejo de errores, métricas y autenticación. Para ilustrarlo, veremos ejemplos prácticos donde se utiliza el decorador `@property` para gestionar atributos en una clase.

Además, aprenderemos a instalar y utilizar módulos externos desde PyPI (Python Package Index), que amplían significativamente las capacidades de Python. Esto incluirá cómo importar módulos, cómo crear un archivo de configuración `setup.py` para paquetes propios y cómo publicarlos en PyPI.

Ejercicio
Implemente un decorador personalizado llamado `tiempo_ejecucion` que muestre el tiempo de ejecución de una función. Luego, aplíquelo a una función matemática cualquiera (por ejemplo, la función `factorial`). Pruebe su implementación y analice los resultados.

Resumen
- Los decoradores son herramientas poderosas para modificar funcionalidades existentes.
- La gestión de módulos externos permite aprovechar el gran ecosistema de Python.