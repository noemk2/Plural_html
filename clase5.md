#interacting with the web with javaScript
el pegamento de la we
ayuda con la interacion del html, el navegador y otros sistemas para hacer que la web sea mas intertivo

Where did Javasript como from?
(de donde viene javaScript)
javaScript es un lenguaje de alto nivel interpretado
interpretado significa que no tiene que compilar el abrigo antes de ejecutar
alto nivel significa que una gran abstraccion de la computadora, lo que sea facil de
de usar
En contraste el lenguaje de programcion c es un lenguaje de bajo nivel es mas complicado pero le da mas control sobre cosas como la administracion de memoria

#history of javaScript
en 1995 cuando el navegador netscape
netscape fue muy popular en los 80 y domino el mercado de los navegadores
el fundador de netscape creia que el navegador necesitaba un lenguaje de pegamento que fuera facil de usar por los diseñadores web
Para este proposito contrato a brandon para integrar este lenguaje de programcion de esquemas en Netscape
creo un prototipo de lo que se llamo life script e 1995

Mas adelante en el año, cuando la primera version se envio con netscape navigator,
cambio su nombre a java script
Como netscape acaba de cerrar el acuerdo con sun para incorporar java en sus productos
javaScript se posiciono como el lenguaje de scripting ligero para la web que complementa el lenguaje de
programacion java, que usaria para colmillos mas robustos
Sin embargo javaScript se parece un poco a java, pero su implementacion se parece mas a una combinacion de esquema de los lenguajes de programacion y de uno mismo
Tambien en 1995, poco despues del lanzamiento de javaScript
Introdujo una implementacion de sitio de servidor fuera de javaScript que funcioaba con netscape enterprise server
En el otro lado del campamento, Microsoft tambien incluyo el lenguaje de scripting en su internet explorer
Utilizando Jscript y Vscript para hacer cosas similares a javaScript
Pero tienen implementaciones diferentes
Crear sitios web que se ejecuten en ambos navegadores fue dificil
Alrededor de 1996, los sitios web aparecieron con mensajes como
Este sitio web es mejor con Netscape
Entonces, en 1996, Netscape creo Javasript ECMA international, una especificacion estandar, al igual que los estandares para HTML y CSS
Tener un estandar alentaria a todos los navegadores web a implementarlo
lo que facilitaria a las personas crear aplicaciones web que funcionen en navegadores antiguos
Esto condujo el primer estandar oficial llamado ECMAScript 1 en 1997
Inplementado por javaScript pero tambien por otros lenguajes como ActionSript y Jscript
El estandar evoluciono con mas funciones en el script ECMAScript 2 en 1998
y la version 3 en 1999
En el año 2000, el trabajo comenzo en la secuencia de comandos de ECMA, pero los esfuerzos del proyecto no
dieron como resultado un estandar y fueron descartados en 2004
En 2000 y siete, el 2007
Implementaciones de Jscript se unieron para impulsar el desarrollo fuera del estandar
Esto dio como resultado el cambio de nombre del
ECMAScript 5
2011 evoluciono a ECMAScript 5.1 mas tarde en 2015
ECMAScript 2015
ECMAScript 2016
ECMAScript 2017
ECMAScript 2018
ECMAScript 2019

hoy en dia los navegadores implementan el estandar de ECMAScript
y amenudos ofrecen funcionalidades qeu solo el estandar
Sigamos llamandolo Javasript, ya que es una implementacion de ECMAScript
elijieron javaScript como lenguaje de alto nivel con el proposito
de facilitar su uso del lenguaje sin la necesidad de compiladores
que tenga un desplieje rapido
O herramientas complicadas
Esto ha sido un punto controversial, ya que muchos desarrolladores lo describen como un lenguaje demaciado simple
y propenso a errores

Sobre todas la adversidades javaScript esta en todas partes y es mas popular que nunca

#What is javaScript
javaScript puede usarse para manipular el navegador y hablar con el servicios

#Making AJAX calls
Otra cosa que podemos hacer con js es hacer llamadas ajax, esto causo furor en el pasado porque usando ajax
podia hacer todo tipo de cosas interactivas y avanzadas desde el navegador sin tener que actualizar la pagina
Por cierto, significa javaScript y xml asincronicos y es solo una cierta tecnica que involucra javaScript
No es una tecnologia adicional
Asi es como funciona en su
Tu navegador web ha cargado un documento html y algo de js que podria provenir de documentos js externos
Ahora, desde el navegador, puede llamar una API externa de la url
esta API puede retornar algo como un documento que luego (documento.txt)
que luego procesas usando js en el navegador
El punto de esto es que el uso de js en el contexto de la tecnica
es usar servicios para referir a una api, sin refrescar tu navegador
Para que los desarrolladores creen paginas mas interactivas

<script>
function loadDoc(){
	var xhtml = new XMLHttpRequest()
	xhttp.onreadystatechange = function(){
		if (this.readyState == 4 && this.status == 200){
			document.getElementById('demo').innerHTML = this.responseText
		}
	}
	xhttp.open('GET', 'ajax_info.txt', true)
	xhttp.sent()
}

</script>

desifrando codigo
tenemos la funcion loadDoc()
esto esta usando ajax
lo que significa que esta usando XMLHttpRequest()
usando este objeto se puede realizar llamadas a servidores que esta en otro lugar sin tener que actualizar la pagina
ESTE ES LA ESENCIA DE de la TECNICA DE AJAX

---

En este caso adjunte este evento llamado xhtttp objeto
Este se dispara cuando el estado del objeto cambia
esto ocurre (el cambio del estado del objeto)
porque cuando se realiza una llamada a un servidor externo
Y hace esto (condicional)
entonces todo salio bien
cambia el texto de demo
y obtiene el texto que se optiene
xhttp.open('GET', 'ajax_info.txt', true)

#Working with js

javaScript es realmente el pegamento de la web
el causante de que las aplicaciones cobren vida e interactuen con el usuario
javaScript no se deriva de java pero se comercializo como un complemento de java
javaScript se parece a java pero funciona de manera diferente
javaScript es lenguaje de programacion de alto nivel que fue creado para ser facil de usar para los desarrolladores y diseñadores
y se puede hacer mucho con el
Puede usar javaScript para interactuar con html y cambiarlo sobre la marcha
usarlo para interactuar con el navegador (crear ventanas emergentes)
tambien iteractuar con camara web y el microfono al que puede accedes el navegador
Y puede usar javaScript para interactuar con otros sistemas como API que viven en servers
Y puedes hacer todo esto si refrescar el navegador para crear una experiencia perfecta para los usuarios

la funcionalidad de javaScript es un estandar que se describe en el standar ECMAScript
Los navegadores web implementan este estandar
ALGUNOS lo hacen al pie de la letra
otros les gusta detras o tienen diferentes implementaciones para las caracteristicas
El punto es que sin herramientas como los navegadores web
ECMAScript es solo un estandar 
Al igual que HTML y CSS 
JAVASCRIPT es solo texto
Esto significa que puede escribirlo desde cero o con editores
O usar la funcionalidad prefabricada de una biblioteca
como jquery o otros
