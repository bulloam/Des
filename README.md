AWS API
AWS API es la interfaz para comunicarse con los recursos de Amazon Web Service. Para beneficio nuestro, existen utilidades de más alto nivel:

AWS CLI
AWS SDK
AWS MANAGEMENT CONSOLE (Consola/GUI)
Probaremos la API de distintas formas, con un ejemplo muy simple de s3.

Amazon s3 - Lista de buckets
Qué es un bucket? Aquí

API directamente
Utilizando ejemplos con Postman... Aquí Pero es muy engorroso, mejor probar las siguientes soluciones!

AWS CLI
Instalación
Iniciar sesión en la CLI
Listar buckets de s3 con AWS CLI, ejecutando en nuestra terminal: aws s3 list
AWS SDK
Realizar los pasos de AWS CLI, para iniciar sesión y poder ejecutar el siguiente código en la consola. En la terminal, dentro de la carpeta "1_api_intro" Utilizando código Python:

Instalar dependencias: pip install -r requirements.txt
Ejecutar código: python sdk.py
AWS Management Console
Bueno, esta es la interfaz gráfica de AWS, que nos sirve para un vistazo más agradable y con varias opciones a un par de clics.
