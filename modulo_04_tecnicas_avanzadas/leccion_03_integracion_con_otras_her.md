# Integracion con otras herramientas

### Objetivos
- Comprender cómo integrar Python con otras herramientas de análisis de datos.
- Aprender a utilizar bibliotecas externas como Pandas y NumPy en proyectos de Python.

### Contenido
La integración de Python con otras herramientas es crucial para potenciar el rendimiento y la funcionalidad de los proyectos. En esta lección, se explorará cómo trabajar eficientemente con bibliotecas populares como Pandas y NumPy, que son fundamentales en el análisis de datos. Pandas ofrece estructuras de datos flexibles y operaciones rápidas para manipular datos, mientras que NumPy proporciona una amplia gama de funciones matemáticas y un manejo eficiente de matrices multidimensionales. A través del uso de estas bibliotecas, los alumnos aprenderán a importar datos desde diferentes fuentes, realizar transformaciones y análisis, y exportar resultados en diversos formatos.

### Ejercicio
Utilice el siguiente código como punto de partida para integrar Pandas con Python:

```python
import pandas as pd

# Cargar un archivo CSV
df = pd.read_csv('datos.csv')

# Mostrar las primeras 5 filas del DataFrame
print(df.head())

# Filtrar los registros donde la columna 'edad' sea mayor que 30
mayores_de_30 = df[df['edad'] > 30]

# Calcular el promedio de la columna 'salario'
promedio_salario = mayores_de_30['salario'].mean()

print("Promedio de salario para mayores de 30 años:", promedio_salario)
```

Modifique este código para:
1. Cargar un archivo Excel en lugar de CSV.
2. Filtrar los registros donde la columna 'edad' sea mayor que 40 y la columna 'salario' sea menor que 50,000.
3. Calcular el promedio de la columna 'salario' para estos registros filtrados.

### Resumen
- Pandas ofrece estructuras de datos robustas y operaciones eficientes para manipular grandes cantidades de datos.
- NumPy proporciona funciones matemáticas avanzadas y un manejo eficiente de matrices multidimensionales, complementando a Pandas en el análisis de datos.