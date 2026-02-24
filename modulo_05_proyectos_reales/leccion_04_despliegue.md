# Despliegue

- Entender los conceptos básicos de despliegue de aplicaciones Python.
- Aprender a configurar y usar un entorno de producción para una aplicación web.

El despliegue de una aplicación Python implica asegurarse de que la aplicación funcione correctamente en un entorno de producción. Esto incluye la elección del servidor, la configuración del entorno de ejecución y el manejo de las dependencias. Para aplicaciones web, es común usar servidores como Gunicorn o uWSGI junto con un servidor web como Nginx para optimizar el rendimiento y la escalabilidad.

Para este ejercicio, se creará una aplicación simple utilizando Flask y se desplegará en un entorno local. Primero, se instalarán las dependencias necesarias y se configurará el archivo `requirements.txt`. Luego, se configurará Nginx para servir la aplicación y Gunicorn para manejar el procesamiento de solicitudes.

- Se ha instalado Flask y sus dependencias.
- Se ha configurado Nginx para servir la aplicación Flask.
- Se ha inicializado Gunicorn para ejecutar la aplicación.