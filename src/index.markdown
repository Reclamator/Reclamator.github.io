<!-- Analytics -->
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-37427094-5', 'auto');
  ga('send', 'pageview');

</script>







### Reclamator
 Realmente recibes el servicio de Internet que pagas?

La idea es exigir mejor calidad de Internet.

Reclamator puede 
- Medir la velocidad de la red en intervalos predefinidos
- Medir la latencia de la red haciendo ping contra un dominio
- Enviar "Tweets" de forma totalmente automática cuando se llega a un porcentaje inferior de la velocidad correspondiente. 

### Descargar
[Windows 10 Beta](../files/windows-x32.7z?raw=true)  
------
[OS X Beta](../files/mac-x32.7z?raw=true)  
------
[Linux Beta](../files/linux-x64.tbz2?raw=true)
------
[Notificarme sobre versiones nuevas](http://eepurl.com/bzMFCT)

### Como funciona?
- Utiliza los servidores de [Ookla Speedtest](speedtest.net) para medir la velocidad.
- Usa TCP Ping para medir la latencia.
- Para enviar tweets utiliza la API de Twitter.

### Como se instala?
1. Descargar el archivo comprimido aquí
2. Descomprimir la carpeta y abrir el ejecutable
3. Crear acceso directo a gusto
![Imagen no disponible :(]](img/1.jpeg?raw=true)

3. Abrir haciendo doble click
![Imagen no disponible :(](img/14.jpeg?raw=true)

### Como se usa?
### 1.) Medir la latencia
1. Ingresar un dominio en el campo, por defecto esta www.google.com
2. Hacer click en Start
![Imagen no disponible :(](img/3.jpeg?raw=true)

3. Va realizando ping indefinidamente hasta que el usuario pare o salga del programa. Todos los valores se guardan en la base de datos local.


### 2.) Medir la velocidad
1. Ingresar en el menu y seleccionar la pantalla velocidad
2. Seleccionar la frecuencia con la la que desea realizar las pruebas de velocidad
3. Luego de hacer click en Start empezara a realizar un test de velocidad en intervalos de la cantidad de minutos especificados, por defecto cada 30 minutos..
![Imagen no disponible :(](img/4.jpeg?raw=true)

### 3.) Visualizar estadísticas 
1. Hacer click en la sección de Estadísticas del menu
2. Al entrar en la sección se mostrara el gráfico de las estadísticas del día actual
3. Para elegir un rango de fecha hacer click arriba en el seleccionador de fechas
4. Dependiendo del tamaño de la base de datos y la velocidad de la computadora, se desplegara el resultado en pocos segundos
![Imagen no disponible :(](img/8.jpeg?raw=true)

5. Haciendo click y arrastrando el mouse sobre el gráfico como se muestra en la imagen, permite hacer “zoom” de esa parte del gráfico 
![Imagen no disponible :(](img/9.jpeg?raw=true)

6. Se puede repetir el proceso de zoom hasta alcanzar una vista cómoda de cada detalle 
![Imagen no disponible :(](img/12.jpeg?raw=true)
![Imagen no disponible :(](img/13.jpeg?raw=true)


### 4.) Configurar Tweets automáticos
1. Ingresar en la parte de Configuraciones del menu
2. Marcar el checkbox “Activar reclamos automáticos”
3. Ingresar el ancho de banda de su conexión. Debe saber con exactitud cuanto ancho de banda corresponde a su plan de Internet, y si varia durante el dia/noche.
4. Seleccionar el porcentaje a partir del cual desea enviar los Tweets. Ej: 70% 
5. Ingresar el mensaje del Tweet, Ej: “Mi internet debería descargar con 1 Mb/s pero solo funciona con el 60% de velocidad”
6. Seguir las Instrucciones para configurar el API Key
7. Una vez guardado correctamente los API Keys y completado todos los datos asegúrese de que el mensaje del Tweet corresponde con el porcentaje y el ancho de banda configurado. 
![Imagen no disponible :(](img/16.jpeg?raw=true "Antes")
![Imagen no disponible :(](img/17.jpeg?raw=true "Despues")


### 3.) Log
1. El log (© Karlheinz Niebuhr) es para ver lo que sucede por detrás de la interface del programa, permite inspeccionar a cada paso la ejecución del código y detectar la  causa de posibles errores.
2. Si desea reportar un error puede contactarme en twitter [@NiebuhrKarl](https://twitter.com/niebuhrkarl)


### 3.) Borrar la base de datos 
1. Entrar en el menu Configuraciones
2. Bajar la pantalla hasta alcanzar los botones rojos 
3. Apretar botón **“Borrar base de datos”** para eliminar toda la configuración personal mas los logs. 
4. Apretar botón **“Borrar Log de Errores”** para eliminar solamente el log de la aplicación 

### Planes para agregarle en el futuro
- Soporte para reclamos por Email etc.. ideas son bienvenidas.. , si estas interesad@ en participar o tenes recomendaciones no dudes en contactarme.
- Publicar en Github con una documentacion detallada


---- 
# F.A.Q.
#### Por que es tan grande el ejecutable?
El software esta implementado en tecnología web, utiliza NW.js que es un runtime basado en Chromium y Node.js. debido a lo cual tiene ese tamaño. 
#### Por que se usa tecnología web para hacer la aplicación?
Porque permite que la aplicación sea multiplataforma y tenga acceso a una variedad de librerías web de buena calidad.
#### Cual es la intension o filosofia detrás de Reclamator?
La idea es mejorar el Internet que sigue siendo pésimo y caro comparado con otros países de la región. 
#### Por que tengo que darle acceso a Internet a la aplicación? 
Reclamator es una aplicación de chequeo del Internet, sin permiso del firewall no puede funcionar. 
#### Por que no esta activado tu Windows?
Porque no uso Windows y solo lo instale en una maquina virtual para hacer las pruebas 
#### Me di cuenta que el directorio de la aplicación se expandió mucho
Esto va pasar con el tiempo ya que la aplicación loquea tanto los eventos del programa como las estadísticas de velocidad y latencia





