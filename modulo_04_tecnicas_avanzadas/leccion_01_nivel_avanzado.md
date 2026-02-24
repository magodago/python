# Nivel avanzado

### Objetivos
- Comprender la optimización de código mediante técnicas avanzadas.
- Aprender a utilizar el módulo `multiprocessing` para mejorar el rendimiento del programa.

### Contenido
En esta lección, se profundizará en técnicas que permiten optimizar el rendimiento y eficiencia del código Python. Se explorará la utilización de la biblioteca `multiprocessing`, que permite ejecutar tareas en paralelo utilizando múltiples procesos, lo cual es especialmente útil para tareas intensivas en CPU o que requieren acceso a recursos externos como bases de datos o archivos.

Se discutirá cómo crear y gestionar procesos utilizando el módulo `multiprocessing`, incluyendo la creación de procesos, comunicación entre ellos mediante colas y pipes, y manejo de excepciones. Se proporcionará un ejemplo práctico donde se implementa una aplicación que realiza cálculos intensivos en paralelo.

### Ejercicio
Implemente un programa que calcule el factorial de números grandes utilizando múltiples procesos para dividir la tarea entre ellos. El programa debe:
1. Pedir al usuario un número entero positivo.
2. Dividir el trabajo entre 4 procesos, cada uno calculando el factorial de una porción del rango de números (por ejemplo, si el número es 100, los procesos pueden calcular el factorial de 1 a 25, 26 a 50, etc.).
3. Utilice `multiprocessing.Queue` para comunicar los resultados entre los procesos.
4. Imprimir el tiempo total necesario para completar la tarea y compararlo con una implementación secuencial.

### Resumen
- Se aprendió cómo utilizar el módulo `multiprocessing` para mejorar el rendimiento de aplicaciones Python mediante la ejecución paralela de tareas.
- Se destacó la importancia de la comunicación entre procesos utilizando colas (`Queue`) y pipes.