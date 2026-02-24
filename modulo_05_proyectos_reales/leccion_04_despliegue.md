# Despliegue

### Objetivos
- Comprender los conceptos básicos de despliegue web para aplicaciones Python.
- Practicar la configuración y publicación de una aplicación Flask en un servidor.

### Contenido
En esta lección, se profundizará en el proceso de despliegue de aplicaciones Python. Se explorará cómo preparar y optimizar una aplicación Flask para su implementación en producción. Se abordarán temas como la elección del entorno de despliegue, configuración de variables de entorno, optimización del rendimiento y seguridad, así como el uso de servicios de hosting como Heroku o AWS. Se proporcionará un ejemplo práctico de cómo preparar una aplicación Flask para su despliegue en Heroku.

### Ejercicio
Despliega una aplicación Flask simple que muestra "¡Hola, mundo!" en tu servidor local y luego publica la misma aplicación en Heroku. Para ello, sigue estos pasos:

1. Crea un archivo `app.py` con el siguiente contenido:
   ```python
   from flask import Flask

   app = Flask(__name__)

   @app.route('/')
   def hello_world():
       return '¡Hola, mundo!'

   if __name__ == '__main__':
       app.run()
   ```

2. Crea un archivo `requirements.txt` con las dependencias necesarias:
   ```
   Flask==2.3.2
   ```

3. Inicializa un repositorio Git y agrega los archivos `app.py` y `requirements.txt`.

4. Configura el archivo `Procfile` para Heroku:
   ```
   web: gunicorn app:app
   ```

5. Crea un archivo `runtime.txt` si estás usando Heroku:
   ```
   python-3.9.16
   ```

6. Realiza la publicación en Heroku utilizando el siguiente comando:
   ```bash
   heroku create tu-aplicacion-nombre
   git push heroku master
   heroku open
   ```

### Resumen
- Se aprendió a preparar y desplegar una aplicación Flask en un servidor de producción.
- Se destacó la importancia de optimización, seguridad y configuración correcta para el despliegue exitoso.