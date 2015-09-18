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
![![Imagen no disponible :(]](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/1.png?raw=true)

3. Abrir haciendo doble click
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/14.png?raw=true)

# Como se usa?
## 1.) Medir la latencia
1. Ingresar un dominio en el campo, por defecto esta www.google.com
2. Hacer click en Start
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/3.png?raw=true)

3. Va realizando ping indefinidamente hasta que el usuario pare o salga del programa. Todos los valores se guardan en la base de datos local.


## 2.) Medir la velocidad
1. Ingresar en el menu y seleccionar la pantalla velocidad
2. Seleccionar la frecuencia con la la que desea realizar las pruebas de velocidad
3. Luego de hacer click en Start empezara a realizar un test de velocidad en intervalos de la cantidad de minutos especificados, por defecto cada 30 minutos..
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/4.png?raw=true)

## 3.) Visualizar estadísticas 
1. Hacer click en la sección de Estadísticas del menu
2. Al entrar en la sección se mostrara el gráfico de las estadísticas del día actual
3. Para elegir un rango de fecha hacer click arriba en el seleccionador de fechas
4. Dependiendo del tamaño de la base de datos y la velocidad de la computadora, se desplegara el resultado en pocos segundos
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/8.png?raw=true)
5. Haciendo click y arrastrando el mouse sobre el grafico como se muestra en la imagen, permite hacer “zoom” de esa parte del gráfico 
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/9.png?raw=true)

6. Se puede repetir el proceso de zoom hasta alcanzar una vista cómoda de cada detalle 
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/12.png?raw=true)
![Imagen no disponible :()](https://github.com/Reclamator/Reclamator.github.io/blob/master/img/13.png?raw=true)



## 4.) Configurar Tweets automáticos
1. Ingresar en la parte de Configuraciones del menu
2. Marcar el checkbox “Activar reclamos automáticos”
3. Ingresar el ancho de banda de su conexión. Debe saber con exactitud cuanto ancho de banda corresponde a su plan de Internet, y si varia durante el dia/noche.
4. Seleccionar el porcentaje a partir del cual desea enviar los Tweets. Ej: 70% 
5. Ingresar el mensaje del Tweet, Ej: “Mi internet debería descargar con 1 Mb/s pero solo funciona con 0.6 o 60%”
6. Seguir las Instrucciones para configurar el API Key
7. Una vez guardado correctamente los API Keys y completado todos los datos asegúrese de que el mensaje del Tweet corresponde con el porcentaje y el ancho de banda configurado.



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
### Por que no esta activado tu Windows?
Porque no uso Windows y solo lo instale en una maquina virtual para hacer las pruebas 







<!-- Analytics -->
<script type="text/javascript">
    (function(i, s, o, g, r, a, m) {
    i['GoogleAnalyticsObject'] = r;
    i[r] = i[r] || function() {
        (i[r].q = i[r].q || []).push(arguments)
    }, i[r].l = 1 * new Date();
    a = s.createElement(o),
        m = s.getElementsByTagName(o)[0];
    a.async = 1;
    a.src = g;
    m.parentNode.insertBefore(a, m)
})(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');

ga('create', 'UA-37427094-5', 'auto');
ga('send', 'pageview');
</script>
