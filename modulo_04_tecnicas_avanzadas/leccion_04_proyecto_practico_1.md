# Proyecto practico 1

### Objetivos
- Implementar un sistema de gestión básica de tareas utilizando clases y objetos.
- Utilizar herencia para crear una jerarquía de clases que represente diferentes tipos de tareas.

### Contenido
En esta lección, se profundizará en el uso avanzado de Python, enfocándose en la creación de un proyecto práctico que implementa un sistema de gestión de tareas. A través del estudio de clases y objetos, los estudiantes aprenderán a organizar y manipular datos de manera eficiente. La lección también abordará la importancia de la herencia para crear estructuras de datos más complejas y flexibles.

Se comenzará por definir una clase base `Tarea` que contendrá atributos comunes a todas las tareas, como el título, la fecha de creación y el estado (pendiente o completada). A continuación, se implementarán clases derivadas que heredarán de `Tarea`, tales como `TareaDiaria`, `TareaSemanal` y `TareaMensual`, cada una con atributos y métodos específicos.

### Ejercicio
Cree un sistema de gestión de tareas básico. Comience definiendo la clase base `Tarea` con los siguientes atributos: `titulo`, `fecha_creacion` (en formato `YYYY-MM-DD`) y `estado` (una cadena que puede ser "pendiente" o "completada"). Luego, implemente una clase derivada `TareaDiaria` que herede de `Tarea` e incluya un atributo adicional `hora` para especificar la hora en la que se debe completar la tarea.

### Resumen
- Se ha creado una clase base `Tarea` con atributos comunes.
- Se ha implementado una jerarquía de clases utilizando herencia para representar diferentes tipos de tareas.
- Se ha definido un atributo adicional en la clase derivada `TareaDiaria`.