# Problemas frecuentes

## Objetivos
- Identificar y corregir errores comunes en Python.
- Analizar y optimizar el rendimiento de código Python.

## Contenido
En esta lección, se abordarán problemas frecuentes que los programadores pueden encontrar al trabajar con Python. Uno de los errores más comunes es la incompatibilidad entre tipos de datos, lo cual puede causar excepciones no capturadas durante la ejecución del programa. Por ejemplo, intentar sumar una cadena y un número directamente generará un error de tipo. Para evitar esto, se recomienda siempre verificar el tipo de los datos antes de realizar operaciones.

Otro problema común es la ineficiencia en el rendimiento del código. Esto puede deberse a bucles innecesarios o al uso excesivo de funciones internas que no están optimizadas para el tamaño del conjunto de datos. Un ejemplo clásico es el uso de listas en lugar de diccionarios cuando se necesita un acceso rápido a elementos basado en una clave.

## Ejercicio
Escribe un programa en Python que calcule la suma de los primeros 1000 números pares y mide su tiempo de ejecución. Primero, utiliza una lista para almacenar los números pares y luego intenta optimizar el código reemplazando la lista por un diccionario. Mide nuevamente el tiempo de ejecución y compara ambos resultados.

## Resumen
- Identificar errores de incompatibilidad entre tipos de datos.
- Optimizar el rendimiento mediante el uso adecuado de estructuras de datos.