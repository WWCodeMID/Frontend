#Etiquetas HTML

###Objetivos
* Agregar algunas etiquetas a tu archivo HTML
* Aprender más sobre etiquetas disponibles

###Panorama

Utiliza las etiquetas para separar bloques de contenido

Las etiquetas trasmiten un significado. Y con el fin de mostrar su contenido, todo debería estar dentro de una etiqueta, no sólo palabras que desees enfatizar. Así que vamos a utilizar la etiqueta paragraph ```<p>``` y la etiqueta header 1 ```<h1>```.

Te darás cuenta que si incluso pones líneas y espacios extra, HTML tratará a cualquier número o línea nueva o espacio de caracteres como otro espacio más. Cuando vayas a empezar con HTML, esto puede resultar trabajoso, por que tienes que escribir

```<p>primer sentencia</p>```

```<p>segunda sentencia</p>```

Cuando sólo quieras una línea en blanco entre de dos sentencias. Pero a medida que vas avanzando, este aspecto de HTML será más útil, porque significa que puedes dar formato a tu código siempre y cuando sea legible para ti, sin preocuparte por lo que el navegador piense de tus líneas y espacios en blanco.

###Etiquetas Anidadas

Es común para una etiqueta HTML estar anidada dentro de otra. En el ejemplo anterior, viste:

```<h1><em> </em></h1>```

#####Nota:

*Sólo asegúrate de que las etiquetas están correctamente anidadas. Por ejemplo, no debes hacer:*

```<h1><em>Hola Mundo!</h1> ¡Me agradas!</em>```

*La etiqueta interior, em, debe cerrarse antes de la etiqueta exterior*

##Pasos
###Paso 1
Agrega más líneas de contenido a tu archivo HTML. Preséntate

```¡Hola <em>Mundo</em>!
Mi nombre es Grisel.```

Ahora guarda el archivo y actualiza tu navegador.
Debes de ver:

![alt tag](https://github.com/WWCodeMID/Frontend/blob/master/img/helloWorld_name.PNG)


###Paso 2
A pesar de que ponemos líneas en blanco, el navegador las ignora. Así que vamos a utilizar etiquetas para romper nuestro contenido

Actualiza tu HTML con la etiqueta h1 y p:

```<h1>¡Hola <em>Mundo</em>!</h1>```

```<p>Mi nombre es Grisel.</p>```

Ahora guarda el archivo y actualiza el navegador.

Debes de ver:

![alt tag](https://github.com/WWCodeMID/Frontend/blob/master/img/helloWorld_name_styles.PNG)

###Paso 3
Ahora agreguemos una lista de cosas que nos gusten.

``` sh
<h1>¡Hola <em>Mundo</em>!</h1>
<p>Mi nombre es Grisel.</p>
<p>Me gusta:</p>
<ul>
  <li>Programar</li>
  <li>Gestión de proyectos</li>
  <li>Jugar LOL</li>
  <li>Dar talleres en WWCode</li>
</ul>
```

Ahora guarda el archivo y actualiza tu navegador.
Debes de ver:

![alt tag](https://github.com/WWCodeMID/Frontend/blob/master/img/list.PNG)


###Explicación
Etiquetas para cada ocasión

El meteórico ascenso de popularidad de la web y la reciente proliferación de aplicaciones web han hecho a HTML muy popular. Aunque originalmente era utilizado sólo para documentos simples, ahora HTML tiene etiquetas para integrar vídeo y reproducir música, incrustación de imágenes, rellenado de formularios web, y todo tipo de etiquetas útiles.

Acabas de utilizar dos etiquetas conocidas, ```h1``` para títulos y ```p``` para párrafos. Pero existen más etiquetas que puedes utilizar:

#####Más Etiquetas

```sh
Etiqueta	    Propósito
a	            Un link (la 'a' significa anchor)
h1-h6	        Varios títulos, h1 es la más importante, h6 es la última.
ul	            Empezar una lista con viñetas (una 'lista desordenada')
ol	            Empezar una lista numerada (una 'lista ordenada')
li	            Cosas dentro de una lista (una 'lista de artículos')
table, tr, td	Puedes hacer tablas (como ésta) con filas y celdas de datos
form	        Un formulario que pueda recoger datos del usuario
input	        un text input, un botón, o un checkbox en un formulario
div	            Un marcador de sección que no hace nada específico al contenido              propio, pero después crea una nueva línea.
span	        Otra sección de marcado que no hace nada en el contenido, pero                 está en línea - no crea una línea después.
```

HTML5 introdujo varias etiquetas nuevas para hacer HTML más semántico, es decir que las etiquetas deben describir el contenido. Algunos de los nuevos elementos introducidos por HTML5 incluyen:

```sh
Etiqueta	    Propósito
section	    Una sección del documento
nav	        Una sección de navegación
header	     El encabezado para una página. (Éste es diferente del elemento head, ¡que contiene metadatos acerca de la página!)
footer	    El pie de página
main	      El contenido importante de la página
aside	     Contenido no esencial
```

¡No trates de memorizar todas las etiquetas! Siempre puedes consultar sitios como:

[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

[DocHub](http://dochub.io/#html/)

Intenta esto:

¿Qué sucede si cambias ```<ul>``` a ```<ol>```? 
(No olvides cambiar la etiqueta de cierre también.)

¿Puedes enlazar tus cosas favoritas a sus respectivas páginas en Wikipedia? 
Aquí hay un ejemplo: ```<a href="http://en.wikipedia.org/wiki/Ruby_(programming_language)">Ruby</a>```

DISCUSIÓN : ¿Cuáles son las partes individuales del código para agregar un enlace?


