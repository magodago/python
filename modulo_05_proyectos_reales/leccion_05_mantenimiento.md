# Mantenimiento

Objetivos
- Comprender la importancia del mantenimiento de código en proyectos Python.
- Aprender técnicas y buenas prácticas para mantener y actualizar códigos existentes.

Contenido
El mantenimiento de código es un aspecto crucial en el desarrollo de software, especialmente cuando se trata con lenguajes dinámicos como Python. Este proceso implica revisar, depurar y optimizar el código ya existente para asegurarse de que siga funcionando correctamente a medida que cambian las necesidades del proyecto o la tecnología. El mantenimiento preventivo también incluye documentar el código adecuadamente y seguir un enfoque modular para facilitar futuras modificaciones.

Las prácticas recomendadas para mantener códigos Python son diversas: asegurarse de que el código cumpla con los estándares PEP 8, revisar regularmente las dependencias y actualizarlas cuando sea necesario, y utilizar herramientas como linters y formatters para mantener un estilo uniforme en todo el proyecto. Además, es importante documentar cambios significativos y realizar pruebas exhaustivas antes de implementar actualizaciones.

Ejercicio
Revisa el siguiente código Python que tiene errores y realiza las correcciones necesarias:

```python
def calcular_area_circulo(radio):
    pi = 3.14
    area = pi * radio**2
    return area

print(calcular_area_circulo(5))
```

Tu tarea es:
- Corregir los errores en el código.
- Documentar la función con un breve comentario que explique su propósito y parámetros.
- Añadir pruebas unitarias para verificar que la función funcione correctamente.

Resumen
- El mantenimiento de código es fundamental para asegurar que las aplicaciones sigan funcionando correctamente a lo largo del tiempo.
- Se recomienda seguir buenas prácticas como documentar el código, utilizar estándares de estilo y realizar pruebas exhaustivas.