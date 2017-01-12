# Registering Services

#The two microservices are running and registered
Vista de los dos servicios corriendo
![Registration service](imagenes/imagen1.png)

Vista desde Account
![Registration service](imagenes/imagen2.png)

Vista desde el Server
![Registration service](imagenes/imagen3.png)

La vista desde la interfaz grafica
La del servidor Eureka, la del puerto 1111 
![Registration service](imagenes/imagen4.png)

Y la del puerto 2222, la de accounts
![Registration service](imagenes/imagen5.png)

Aquí se aprecian los tres servicios 
![Registration service](imagenes/imagen6.png)

Y aquí se ve la web
![Registration service](imagenes/imagen7.png)

#The service registration service has the two microservices registered 
Aquí se pueden ver dos servicios, el Accounts-service y Web-service
![Registration service](imagenes/imagen8.png)

#A second account microservice is running in the port 4444 and it is registered 
![Registration service](imagenes/imagen9.png)
![Registration service](imagenes/imagen10.png)

#A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
Se elimina el Account del puerto 2222
![Registration service](imagenes/imagen11.png)
Al ser eliminado se ve como se ha perdido la conexion
![Registration service](imagenes/imagen12.png)
Se ve como el Account del puerto 4444 sigue vivo
![Registration service](imagenes/imagen13.png)

Lo que realmente ha pasado es que ha realizado un reemplazo de Account en caliente.

Te añado un pdf en la carpeta /imagenes donde estan las capturas.