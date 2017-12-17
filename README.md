# Arreglo_ruta

Se desarrolla la situacion de GEOLOCALIZACION. 

Elaborado en HTML5 usando el API de JAVASCRIPT de Google: https://developers.google.com/maps/documentation/javascript/tutorial?hl=es-419

# GeoRuta. (ruta.html)

En este se resuelve la situacion de un punto y la ruta entre dos ciudades, para evaluar si el punto(marcador) esta dentro de la ruta.

Basado en la documentación de Google, que colocare a continuacion:
Se parte del ejemplo como plantilla y se desarrolla el trabajo en el.

Creacion y dibujo de ruta: https://developers.google.com/maps/documentation/javascript/examples/directions-waypoints

Se obtiene todos los puntos de la ruta, para realizar formula de distancia entre dos puntos y con respecto a la variable 'range' determinar
que tan preciso sea la distancia del punto a la ruta. la variable range esta prefijada en 0.004. pero para necesidades del cliente se puede
modificar.

Si el punto(marcador) enta dentro el rango (range) en cuestion, entonces se determina que hace parte de la ruta, en caso contrario no se
toma como parte de la ruta.

Funcionamiento:

Necesita de las coordenadas del marcador para fijar la posicion del punto, se recomienda usar la siguiente posicion :

x (longitud) = -75.368
y (latitud) = 6.427530

Este punto esta dentro de la ruta: MEDELLIN - CARTAGENA. Por lo cual tambien se recomienda usar dicha ruta en la seleccion de
Origen(Medellin) y Destino(Cartagena).

Este punto cumple con la condiccion y el panel lateral derecho marcara que SI esta dentro del punto.

se puede cambiar las ciudades de origen y destino, de acuerdo a la lista preestablecida.

Luego de ajustar coordenadas y ruta, click en boton enviar.

# GeoCerca (reto.html)

En este se resuelve la situacion de un punto y una geocerca ( rectangulo geografico), para evaluar si el punto (marcador) esta dentro de
la Geocerca.

Basado en la siguiente documentacion de Google:

marcadores: https://developers.google.com/maps/documentation/javascript/markers

Biblioteca de Dibujo: https://developers.google.com/maps/documentation/javascript/drawinglayer?hl=es

Dibujo de Geocerca (rectangulo) : https://developers.google.com/maps/documentation/javascript/examples/rectangle-simple

Funcionamiento:

Necesita de las coordenadas del marcador para fijar la posicion del punto, se recomienda usar la siguiente posicion :

x (longitud) = -75.558
y (latitud) = 6.310

Dicho punto esta dentro de la region del rectangulo.

El rectangulo esta prefijado en posicion, pero la adquisicion de las coordenadas si es dinamica de acuerdo a la GeoCerca.

Tiene de validacion de datos con respecto a un nulo, es decir, es necesario ingresar las coordenadas.

Luego de ingresar coordenadas, click en el boton 'ingresar coordenadas'.

una nube informativa, nos indicara si el punto esta dentro o fuera de la Geocerca.



