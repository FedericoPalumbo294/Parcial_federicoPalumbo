# ParcialDiseño
## Pasos para ejecutar el programa
### Paso 1
Instala las dependencias requeridas ejecutando el siguiente comando en la terminal: pip install -r requirements.txt
### Paso 2
Inicia el programa ejecutando el archivo principal con el siguiente comando: python3 app.py
### Paso 3
Abrir postman y abrir el archivo que se encuentra en la carpeta collection
### Paso 4
En Postman, selecciona el request POST para enviar una secuencia de ADN y verifica si es mutante. Ingresa una secuencia de dna en el cuerpo de la solicitud y envíala.
### Paso 5
Para obtener estadísticas, selecciona el request GET en Postman para ver el número de mutantes y no mutantes registrados en la base de datos.


Postman se ejecutara en esta URL: http://127.0.0.1:5000/

## Como esta dockerizado y hosteado con render solo hace falta abrir postman y poner las siguientes url:
### Para realizar el POST:
https://parcialdise-o-1.onrender.com/mutant 
### Para realizar el GET de las estadisticas:
https://parcialdise-o-1.onrender.com/stats 
