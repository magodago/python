# Despliegue

- Entender los conceptos básicos de despliegue web para aplicaciones Python.
- Aprender a configurar un servidor local utilizando Flask o Django.

## Contenido
En esta lección del módulo Proyectos reales, nos enfocaremos en el despliegue de nuestras aplicaciones Python. El despliegue es crucial para que nuestro código funcione eficientemente en entornos externos a nuestra máquina de desarrollo. Usaremos Flask y Django como frameworks web para demostrar cómo configurar un servidor local. Flask es una herramienta ligera y flexible, ideal para proyectos pequeños o prototipos rápidos. Por otro lado, Django ofrece características más avanzadas y estándares robustos, perfecto para aplicaciones de mayor complejidad.

Para configurar el servidor local con Flask, primero instalaremos las dependencias necesarias a través del archivo `requirements.txt`. Luego, creamos un simple archivo `app.py` que define nuestro servidor web. Usando comandos como `flask run`, podremos ejecutar nuestra aplicación en un servidor local y verla funcionar en el navegador.

## Ejercicio
Configura un proyecto Flask básico siguiendo los siguientes pasos:
1. Crea un nuevo directorio para tu proyecto.
2. Instala Flask usando pip: `pip install flask`.
3. Crea un archivo `app.py` con el siguiente contenido:
   ```python
   from flask import Flask

   app = Flask(__name__)

   @app.route('/')
   def hello_world():
       return '¡Hola, mundo!'

   if __name__ == '__main__':
       app.run()
   ```
4. Ejecuta tu aplicación con `flask run` y verifica que funcione en el navegador.

## Resumen
- Se aprendió a configurar un servidor local para una aplicación Flask.
- Se destacó la importancia del despliegue en el ciclo de vida de un proyecto Python.