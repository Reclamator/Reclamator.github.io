# Reclamator
 Realmente recibes el servicio de Internet que pagas?

La idea es exigir mejor calidad de Internet.

Reclamator puede 
- Medir la velocidad de la red en intervalos predefinidos
- Medir la latencia de la red haciendo ping contra un dominio
- Enviar "Tweets" de forma totalmente automática cuando se llega a un porcentaje inferior de la velocidad correspondiente. 

# Como funciona?
- Utiliza los servidores de [Ookla Speedtest](speedtest.net) para medir la velocidad.
- Usa TCP Ping para medir la latencia.
- Para enviar tweets utiliza la API de Twitter.

# Como se instala?
1. Descargar el archivo comprimido aquí
2. Descomprimir la carpeta y abrir el ejecutable
3. Crear acceso directo a gusto
![![Imagen no disponible :(]](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/1.png)
3. Abrir haciendo doble click
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/14.png)
4. Navegar por el menu de la izquierda



# Como se usa?
## 1.) Medir la latencia
1. Ingresar un dominio en el campo, por defecto esta www.google.com
2. Hacer click en Start
3. Mientras va midiendo se guardan en la base de datos los valores de las respuestas para que después estén disponibles desde la pantalla de Estadísticas.


## 2.) Medir la velocidad
Ingresar en el menu y seleccionar la pantalla velocidad
Seleccionar la frecuencia con la la que desea realizar las pruebas de velocidad
Luego de apretar Start empezara a realizar un test de velocidad en intervalos de la cantidad de minutos especificados, por defecto cada 30 minutos..

## 3.) Configurar Tweets automáticos
Ingresar en la parte de Configuraciones del menu
Marcar el checkbox “Activar reclamos automáticos”
Ingresar el ancho de banda de su conexión. Debe saber con exactitud cuanto ancho de banda corresponde a su plan de Internet, y si varia durante el dia/noche.
Seleccionar el porcentaje a partir del cual desea enviar los Tweets. Ej: 70% 
Ingresar el mensaje del Tweet, Ej: “Mi internet debería descargar con 1 Mb/s pero solo funciona con 0.6 o 60%”
Seguir las Instrucciones para configurar el API Key
Una vez guardado correctamente los API Keys y completado todos los datos asegúrese de que el mensaje del Tweet corresponde con el porcentaje y el ancho de banda configurado.



---- 
# FAQ
### Por que es tan grande el ejecutable?
El software esta implementado en tecnología web, utiliza NW.js que es un runtime basado en Chromium y Node.js. debido a lo cual tiene ese tamaño. 
### Por que se usa tecnología web para hacer la aplicación?
Porque permite que la aplicación sea multiplataforma y tenga acceso a una variedad de librerías web de buena calidad.
### Cual es la intension o filosofia detrás de Reclamator?
La idea es mejorar el Internet que sigue siendo pésimo y caro comparado con otros países de la región. 
### Por que tengo que darle acceso a Internet? 
Reclamator es una aplicación de chequeo del Internet, sin permiso del firewall no puede funcionar. 
