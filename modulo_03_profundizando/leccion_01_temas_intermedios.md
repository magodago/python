# Temas intermedios

- Comprender la utilización de decoradores en Python y sus aplicaciones prácticas.
- Aprender a trabajar con context managers para gestionar recursos eficientemente.

Python es un lenguaje de programación versátil que ofrece características avanzadas para mejorar la eficiencia y claridad del código. En esta lección, profundizaremos en dos temas intermedios: decoradores y context managers. Los decoradores son una forma elegante de modificar funcionalidades existentes sin alterar su estructura interna. Por ejemplo, podrás crear un decorador que mide el tiempo de ejecución de una función o añade loggear a otra. Context managers, por otro lado, permiten administrar recursos de manera eficiente, asegurando que se liberan correctamente cuando ya no son necesarios. Usualmente, esto se hace utilizando la instrucción `with`, que garantiza la ejecución de bloques de código antes y después del bloque principal.

Ejercicio: Crea un decorador que muestre el tiempo de ejecución de una función. Luego, aplica este decorador a diferentes funciones matemáticas para medir su rendimiento. Además, escribe un context manager que maneje archivos, asegurándose de que se cierran correctamente después de su uso.

- Decoradores permiten modificar funcionalidades sin alterar el código base.
- Context managers facilitan la gestión eficiente de recursos como archivos o conexiones a bases de datos.