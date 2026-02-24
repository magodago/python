# Pruebas y validacion

Objetivos
- Comprender la importancia de las pruebas y validación en proyectos de Python.
- Implementar técnicas básicas de pruebas unitarias utilizando `unittest` para asegurar la calidad del código.

Contenido
Las pruebas y validaciones son fundamentales en el desarrollo de software, ya que permiten detectar errores temprano en el proceso, lo cual reduce costos y mejora la calidad final. En Python, se puede utilizar el módulo `unittest` para escribir pruebas unitarias. Este módulo proporciona una forma estructurada de definir y ejecutar pruebas, asegurando que las funciones y métodos funcionen como esperado bajo diferentes condiciones.

Para ilustrar esto, consideremos un ejemplo simple: un programa que calcula el área de un círculo. Podríamos escribir una función `calcular_area` que tome el radio como parámetro y devuelva el área. Con `unittest`, podríamos crear pruebas para verificar que la función funcione correctamente con diferentes radios, incluyendo casos borde como un radio de 0.

Ejercicio
Implemente las pruebas unitarias para la función `calcular_area` utilizando el módulo `unittest`. Cree al menos tres pruebas: una para un radio normal, otra para un radio igual a cero y una última para un radio negativo. Asegúrese de que sus pruebas capturan los comportamientos esperados.

Resumen
- Las pruebas unitarias son esenciales para garantizar la calidad del código.
- `unittest` en Python ofrece un marco robusto para escribir y ejecutar pruebas.
- Es importante cubrir tanto casos normales como borde en las pruebas.