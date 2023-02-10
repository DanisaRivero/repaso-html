# CAPA DE PRESENTACIÓN:

atributo `float` es de un elemento al que quieras poner en cualquier lado, sin que los
elementos en bloque vayan justamente por debajo del elemento al que usaste con float.
*en términos criollos jeje* 

## Medias queries

En español *consulta de medios* son útiles cuando deseas modificar tu página web o aplicación en función del tipo de dispositivos (como una impresora o una pantalla) o de caraterísticas y parámetros específicos (como la resolución de la pantalla o el ancho del `viewport` del navegador).

### Ejemplos:
~~~ css
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {...}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 601px) and (max-width: 767px) {...}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) and 991px {...}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) and 1199px {...}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {...}
~~~
> Para qué sirven los breakpoints en css?
* Para definir los píxeles en los cuales la pantalla debe cambiar el layout según el dispositivo.

> Propiedad para aplicar a las imágenes para que no se deformen cuando trabajamos en responsive es:
~~~ css
img{
  max-width: 100%;
  height: auto;}
~~~

otra ayuda para media queries
~~~ css
/* Dispositivos pequeños (celulares) */
@media screen and (max-width: 767px){...}

/* Dispositivos medianos (tablet) */
@media screen and (min-width: 768px) and (max-width: 1023px){...}

/* Dispositivos grandes (pc, escritorio, laptops) */
@media screen and (min-width: 1024){...}

~~~
