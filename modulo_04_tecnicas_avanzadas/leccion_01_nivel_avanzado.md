# Nivel avanzado

### Objetivos
- Comprender y aplicar técnicas avanzadas de programación orientada a objetos.
- Implementar y optimizar la utilización de decoradores en Python.

### Contenido
En esta lección del módulo de técnicas avanzadas, se profundizará en el uso de metaclasses y decoradores para abordar problemas complejos de una manera más eficiente. Los metaclasses son una característica avanzada que permite controlar la creación de clases en Python, permitiendo modificar o personalizar su comportamiento durante la definición de la clase. Decoradores, por otro lado, son funciones que toman otra función y extienden su funcionalidad sin modificarla directamente, lo cual es muy útil para añadir funcionalidades a métodos o funciones existentes.

Para ilustrar estos conceptos, se explorará un caso práctico donde se utilizarán metaclasses para controlar la creación de clases con atributos dinámicos y decoradores para loggear el acceso a métodos y propiedades de una clase, mejorando así la trazabilidad del código.

### Ejercicio
Implemente un ejemplo simple utilizando metaclasses. Cree una metaclass que registre todas las clases creadas durante su ejecución en una lista. Luego, utilice esta metaclass para crear varias clases y verifique si se están registrando correctamente.

### Resumen
- Metaclasses permiten controlar la creación de clases y pueden ser utilizadas para personalizar el comportamiento de clases.
- Decoradores son una técnica avanzada que permite extender funcionalidades de funciones o métodos sin modificarlos directamente, mejorando así la legibilidad y mantenibilidad del código.