# Temas intermedios

- Comprender la utilización de las excepciones y manejo de errores en Python.
- Implementar funciones recursivas y comprender sus implicaciones.

Python es una potente herramienta para la programación general, pero su verdadero poder se despliega cuando se dominan conceptos más avanzados. En esta lección, profundizaremos en dos temas cruciales: el manejo de excepciones y las funciones recursivas. El manejo adecuado de excepciones es fundamental para desarrollar software robusto que pueda manejar errores de manera gracia. Las funciones recursivas, por otro lado, permiten abordar problemas complejos de forma elegante y eficiente.

Para ilustrar estos conceptos, considera un ejemplo donde necesitas leer datos desde un archivo. Sin el manejo adecuado de excepciones, un error como un archivo no encontrado podría interrumpir la ejecución del programa. Con las excepciones, puedes capturar este error y tomar medidas apropiadas, tal vez mostrando un mensaje al usuario o intentando recuperar los datos desde una fuente alternativa.

En cuanto a las funciones recursivas, estas son funciones que se llaman a sí mismas durante su ejecución. Un ejemplo simple podría ser una función para calcular el factorial de un número. La funcionalidad básica sería: si el número es 1, devolver 1; en caso contrario, multiplicar el número por el resultado de la misma función con el número decrementado en uno.

### Ejercicio
Implementa una función que calcule el factorial de un número utilizando recursividad. Luego, añade un bloque `try-except` para manejar posibles errores, como ingresar un valor no numérico o negativo.

### Resumen
- Manejo de excepciones permite desarrollar software más robusto.
- Las funciones recursivas son útiles para resolver problemas complejos de manera elegante.