Proyecto ParcialDiseño
Guía para ejecutar el programa
Paso 1
Instalar las dependencias necesarias usando el siguiente comando en la terminal:

bash
Copiar código
pip install -r requirements.txt
Paso 2
Ejecutar la aplicación iniciando el archivo principal con el comando:

bash
Copiar código
python3 app.py
Paso 3
Abrir Postman y cargar la colección que se encuentra en la carpeta collection.

Paso 4
En Postman, seleccioná el request POST para analizar si una secuencia de ADN corresponde a un mutante. Ingresá la secuencia en el cuerpo de la solicitud y envíala.

Paso 5
Para ver las estadísticas, seleccioná el request GET en Postman, el cual muestra la cantidad de mutantes y no mutantes almacenados en la base de datos.

La aplicación estará disponible localmente en la siguiente URL:

arduino
Copiar código
http://127.0.0.1:5000/
URLs para ambiente dockerizado (hosteado en Render)
Para hacer un POST:

bash
Copiar código
https://parcialdise-o-1.onrender.com/mutant
Para consultar las estadísticas (GET):

bash
Copiar código
https://parcialdise-o-1.onrender.com/stats
