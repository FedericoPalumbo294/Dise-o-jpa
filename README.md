Instrucciones para ejecutar el programa
Paso 1: Instalar dependencias
Ejecutá este comando en la terminal para instalar todas las dependencias necesarias:

bash
Copiar código
pip install -r requirements.txt
Paso 2: Iniciar el programa
Lanzá el programa ejecutando:

bash
Copiar código
python3 app.py
Paso 3: Configurar Postman
Abrí Postman y cargá la colección que está en la carpeta collection.

Paso 4: Verificar secuencia de ADN (POST request)
En Postman, seleccioná el request POST para enviar una secuencia de ADN y verificar si es mutante.
Ingresá una secuencia de dna en el cuerpo de la solicitud (en formato JSON) y enviála.
Paso 5: Obtener estadísticas (GET request)
Para ver el número de mutantes y no mutantes registrados, seleccioná el request GET en Postman.
URLs para pruebas en Postman
Local (cuando ejecutás el programa en tu máquina):
http://127.0.0.1:5000/

Servidor (Dockerizado y hosteado en Render):

Verificar ADN (POST):
https://parcialdise-o-1.onrender.com/mutant

Obtener estadísticas (GET):
https://parcialdise-o-1.onrender.com/stats

