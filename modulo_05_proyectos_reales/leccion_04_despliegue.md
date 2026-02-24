# Despliegue

- Comprender los conceptos básicos de despliegue de aplicaciones Python.
- Implementar un despliegue básico utilizando servicios de hospedaje web.

El despliegue de una aplicación Python implica asegurarse de que tu código esté accesible en la red. Esto puede hacerse a través de varios métodos, dependiendo del escenario y las necesidades específicas. En este módulo, aprenderás sobre el despliegue básico utilizando servicios de hospedaje web como Heroku o PythonAnywhere. Estos servicios permiten subir tu código y ejecutarlo en un servidor remoto, lo que significa que cualquier usuario puede acceder a tu aplicación desde cualquier lugar con una conexión a internet.

Para ilustrar este concepto, vamos a practicar el despliegue de una pequeña aplicación Flask utilizando Heroku. Primero, asegúrate de tener instalado Flask y Git en tu máquina local. Luego, crea un archivo `app.py` con un simple "Hello World" y configura un archivo `requirements.txt` para especificar las dependencias necesarias. Finalmente, utiliza el comando `heroku create` seguido de `git push heroku master` para subir tu aplicación a Heroku.

- Comprender los pasos básicos del despliegue utilizando servicios web.
- Practicar la configuración y publicación de una aplicación Flask en Heroku.