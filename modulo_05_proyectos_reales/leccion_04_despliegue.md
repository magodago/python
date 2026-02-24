# Despliegue

- Entender los conceptos básicos de despliegue de aplicaciones Python.
- Aprender a configurar un entorno de desarrollo local para el despliegue.

El despliegue de una aplicación Python implica la implementación de tu código en un entorno que permita su ejecución y acceso desde diferentes dispositivos. Este proceso puede variar dependiendo del tipo de aplicación (web, desktop, móvil) y del framework o biblioteca utilizada. En este módulo, se enfocará en el despliegue de aplicaciones web utilizando Flask, un framework popular para Python.

Para configurar tu entorno local, es necesario instalar Python y un servidor web como Gunicorn junto con una base de datos si la aplicación lo requiere (por ejemplo, PostgreSQL o SQLite). Se recomienda usar un entorno virtual para aislamiento y gestión de dependencias. Posteriormente, se realizará el despliegue en un servidor remoto utilizando servicios como Heroku o AWS.

### Ejercicio
Desarrolla una pequeña aplicación web con Flask que muestre "¡Hola, mundo!" en la página principal. Luego, configura y ejecuta esta aplicación localmente usando Gunicorn. Finalmente, despliega tu aplicación en un servidor de prueba como Heroku.

- Comprender el proceso de configuración del entorno local.
- Realizar el despliegue local utilizando Gunicorn.
- Implementar la aplicación en un servidor remoto.