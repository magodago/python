# Optimizacion

- Optimizar el rendimiento de los programas Python mediante la utilización eficiente de estructuras de datos.
- Implementar técnicas de programación funcional para mejorar la eficiencia y legibilidad del código.

Python es una potente herramienta que, al ser interpretada, necesita optimizaciones específicas para mejorar su rendimiento. Para abordar esto, se pueden utilizar varias estrategias. Una de ellas implica el uso adecuado de estructuras de datos como listas, diccionarios y conjuntos, seleccionando la más apropiada según las necesidades del programa. Por ejemplo, si se necesita acceder a elementos por clave, un diccionario es preferible a una lista. Además, comprender cómo Python maneja el reciclaje de memoria para estas estructuras puede optimizar el uso de recursos.

El segundo objetivo es familiarizarse con técnicas de programación funcional que pueden mejorar la eficiencia del código. Esto incluye el uso de funciones lambda y map/reduce para procesar listas de manera más eficiente, así como comprender cómo Python maneja las funciones como objetos y su uso en combinación con otras estructuras de datos.

### Ejercicio
Escribe un programa que calcule la suma de los primeros 1000 números pares utilizando una lista comprehension y luego usando map/reduce. Compara el rendimiento de ambos métodos utilizando `timeit` para ver cuál es más eficiente en tu entorno local.

### Resumen
- Seleccionar las estructuras de datos adecuadas según la necesidad del programa.
- Utilizar técnicas de programación funcional como map/reduce y funciones lambda para mejorar la eficiencia.