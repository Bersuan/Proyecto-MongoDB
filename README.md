# Proyecto-MongoDB

![alt text](https://github.com/Bersuan/Proyecto-MongoDB/blob/master/input/portada-esports.jpg)

### ¿Donde situarias tu empresa

En este proyecto se nos presentaba la oportunidad de geolocalizar la mejor ubicación para crear nuestra Startup: "GAMING Industry" para ello contabamos con el siguiente equipo:

20 diseñadores.\
5 ingenieros de UI / UX.\
10 desarrolladores frontend.\
15 ingenieros de datos.\
5 desarrolladores de backend.\
20 gerentes de cuenta.\
1 mantenimiento que ama el baloncesto.\
10 ejecutivos.\
1 CEO / Presidente.

Como ingeniero de datos, nos pedido a todos los empleados que muestren sus preferencias sobre dónde ubicar la nueva oficina. Su objetivo es colocar las nuevas oficinas de la compañía en el mejor lugar para que la compañía crezca. Tienes que encontrar un lugar que cubra más o menos todos los siguientes requisitos. Tenga en cuenta que es imposible cubrir todos los requisitos , por lo que debe priorizar a simple vista.

A los diseñadores les gusta ir a charlas de diseño y compartir conocimientos. Debe haber algunas empresas cercanas que también hacen diseño.
El 30% de la empresa tiene al menos 1 hijo.
A los desarrolladores les gusta estar cerca de startups tecnológicas exitosas que han recaudado al menos 1 millón de dólares.
A los ejecutivos le gusta MUCHO Starbucks. Asegúrese de que hay un Starbucks no muy lejos.
Los gerentes de cuentas necesitan viajar mucho
Todas las personas en la empresa tienen entre 25 y 40 años, deles un lugar para ir de fiesta.
A nadie en la compañía le gusta tener compañías con más de 10 años en un radio de 2 KM.
El CEO es vegano

En nuestro estudio, hemos comenzado filtrando aquellas empresas tecnológicas que habian ganado mas de $1M, desde una base de datos de MogngoDb.

EL segundo filtro, ha sido priorizar la actualidad, y viendo donde se situaban la mayoria de esas empresas y aprovechando el "BOOM" Gaming de Londres, nos decantamos por colocar nuestra oficina en esa ciudad.
https://www.bbc.com/news/newsbeat-51400755

El tercer filtro ha sido buscar buscar coegios por la zona en un radio de 2km para que los padres de nuestra empresa puedan llevar a sus hijos sin perder mucho tiempo, para conseguir estas geolocalizaciones hemos usado la API de google, lanzando las requests necesarias para obetener la informacion deseada.

EL cuarto filtro, tambien mediante la APi de Gooogle ha sido geolocalizar los sitios de fiesta mas frecuentados de londres, ya que como a todo londinese, nos gusta el after work tomando una buena pinta en un tipico pub ingles, fomentando asi la unidad del equipo.

El quiento filtro, atendiendo a las necesidades del CEO, ha sido, el de geolocalizarle algunos restaurantes veganos para que pueda comer todos los dias sin tener que preocuparse por lo que come o tener que pedir a Deliveroo. La posición la hemos obtenido también utilizando la APi de google, filtrando por restaurantes y con le keyward "vegan".

EL sexto filtro ha sido geolocalizar la posicion de los starbucks de Londres y con ello satisfacer las necesidades de los ejecutivos. Para ello nos hemos descargado un dataset de kaggle del cual hemos obtenido sus coordenadas. https://www.kaggle.com/starbucks/store-locations

El ultimo filtro, y no por ello menos importamte, a sido el de tener un aereopuerto cerca, teniendo el famoso aereopurto de HEatrow a menos de 40 minutos. Para localizar la posicion de los aerreopuertos hemos usado el siguiente dataset: https://ourairports.com/data/

Una vez realizados estos filtros nos ha salido la geolocación perfecta para el bienestar comun de nuestra empresa, situandose esta en: 

![alt text](https://github.com/Bersuan/Proyecto-MongoDB/blob/master/input/Mapa-Geolocalizaci%C3%B3n.png)

##### 2 Catherine St Londres, Inglaterra
##### Latitud: 51.512051 | Longitud: -0.120488

El punto negro representa la localizción de nuestra empresa.\
El punto rojo son aquellas startups que ha ganado mas de $1Millon.\
El punto naranja son los lugares para el afterwork.\
El punto amarillo son aquellos colegios a los cuales los empleados pueden llevar a sus hijos.\
El punto morado son los restaurantes veganos para el CEO.\
El punto verde son los Starbucks que tanto gusta.\
Y aunque el punto azul no aparece (aerepuerto) tenemos el de Heatrow a 40 minutos.





