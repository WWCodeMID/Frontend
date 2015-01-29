#Introduccion A HTML

###Objetivos

* Crear un archivo HTML en blanco
* Ver cómo el archivo es interpretado por el navegador

###Panorama

#####¿Qué es HTML?

 
HTML significa Hyper-text Markup Language.

Vamos a revisar y explicar cada una de estas palabras en orden inverso...

* Language - La gente utiliza diferentes lenguajes para diferentes tipos de comunicación. Usamos lenguajes tales como el Inglés y el Mandarín para la comunicación humana o lenguajes como Ruby o Java para dar instrucciones a la computadora. HTML es un lenguaje especial para describir documentos.

* Markup - Ser un lenguaje de marcado significa que HTML está mezclado con contenido de texto plano. Piensa en alguna ocasión en la que hayas entregado un ensayo a tu maestro. El maestro lee el ensayo y lo marca con comentarios o sugerencias, agregando información extra en la parte superior del contenido del texto.

* Hyper-text - Este término proviene de que las primeras computadoras solo podían trabajar con archivos de texto plano. Los usuarios de los 60s quisieron enriquecer este texto y hacerlo más fácil de trabajar. Así, el hipertexto nació. Es texto porque el archivo es almacenado como texto plano, pero es hyper ya que el texto tiene un significado especial más allá del texto plano cuando es interpretado por un programa especial. Para HTML, ese programa especial es tu navegador.

#Pasos
###Paso 1
Necesitarás arrancar tu editor de texto (como Sublime Text, Komod Edit, o Text Wrangler) para estos pasos. ¡Haremos un documento HTML!

Crea un nuevo archivo y nómbralo **hello.html **. (En algunos editores, puede que necesites agregar el tipo de archivo 'HTML'; pero usualmente, la extensión .html será suficiente.)

![alt tag]()

Nota que la extensión es .html. Le indica al navegador que el contenido lo debe desplegar como HTML.

Escribe en el documento HTML que acabas de crear:

```sh
¡Hola Mundo!
```
Guarda el archivo en un lugar donde puedas encontrarlo fácilmente. Como sugerencia crea tu carpeta de Frontend.

###Paso 2
Abre Chrome y ve al menú Archivo, Abrir Archivo, después selecciona el archivo de tu escitorio o de cualquier lugar donde lo hayas puesto.

![alt tag]()

Aunque tu archivo no contenga una etiqueta HTML aún, los navegadores son buenos mostrando texto en pantalla, así que el navegador te mostrará tu texto.

###Paso 3
Un poco aburrido, ¿verdad? Para hacerlo lucir un poco menos plano, agregemos una etiqueta HTML. 

Actualiza el contenido de tu archivo hello.html para que luzca así:
```sh
¡Hola <em>Mundo</em>!
```

La etiqueta HTML em le dice a tu navegador que agregue énfasis a esa cadena de texto. Recarga tu navegador y verás el efecto:

![alt tag]()

###HTML son Etiquetas

El navegador necesita mas información que solamente la extensión del archivo para desplegar el contenido de sitio web. La manera en que proveemos esa información es marcando tu texto con pistas de contenido en la forma de etiquetas HTML ¡Que es lo que acabas de hacer, agregando la etiqueta ```<em>``` a tu página!

Una etiqueta HTML está encerrada entre paréntesis angulares, los cuales lucen así: <,>. La mayoría de las etiquetas tienen una etiqueta de cierre con una diagonal. Las etiquetas describen el contenido que encierran, en nuestro ejemplo, haciendo énfasis en la palabra "mundo".

Etiqueta de apertura: ```<em>```

Contenido: Mundo

Etiqueta de cierre: ```</em>```

Y todas estas cosas combinadas—etiqueta de apertura, contenido, y etiqueta de cierre—son llamadas elementos HTML: ```<em>Mundo</em>```








