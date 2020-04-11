# 4 styling web with css

Mostrar texto e imagenes en la web es agradable, pero debemos poder diseñar el contenido para que sea legible y
utilizable. Veremos como hacer eso en este modulo mientras hablamos sobre como darle estilo a la web con CSS o Cascading Style Sheet

contexto sobre el origen de css
Esto lo ayudara a comprender que es css y porque es importante antes de ver de donde proviene
Echemos un breve vistazo a lo que es
Aqui eta el sitio web Cookies

en el inspector (elements) podemos ver 2 ventanas una de html y otra de css

Hojas de stilo en cascada es un lenguaje de hojas de stilo que se utliza para describir la presentacion de un documento
como acabamos de ver
Tambien hay otros lenguajes de hoja de estilo para diseñar diferentes cosas
como XML ve qeu S es uno de esos y es el mas importante para la web
Ahora echamos un breve vistazo al historia web

1994 se propuso como lenguaje de hoja de estilo se propusieron otros idiomas en ese momento. Sin embargo, W tree see o el
1996 resultado de la recomendacion oficial del estandar CSS version 1 , al principio havia poco soporte de los navegadores
1998 css se continuo desarrollando lo que origino la publicacion de la recomendacion del nivel 2 css
paso mucho tiempo hasta haya nuevas versiones fuera del estandar
aunque el soporte del navegador mejoro cada vez mas hasta que en 2000 y cuatro temporadas, el nivel 2.1 se
convirtio en recomendacion candidata
2004 CSS2.1 candidata como recomendacion
2011 CSS2.1 recomendacion oficial .. esto no era una recomendacion sino una serie de modulos categoria de capacidades
esto dio como resultado la publicacion v3
2011 CSS3-selectors CSS3-color

las recomendaciones oficiales para mas modulos de arbol css surgieron como el modulo css
2012 Therr media queries en 2012 y el modulo css tree you y e 2017
2017 CSS3-UI
2017 Los desarrollos futuros de la especificaciones CSS siguen al principio del modulo en el que algunos modulos alcanzan el nivel cuatro y se introducen nuevos modulos como modulos de nivel uno, como los libros CSS Flex, recomendacion de candidato de nivel uno en 2017

Es importante recordar que todas estas versiones continen diferentes capacidades fuera de CSS y estan determinadas por comisiones como el consorcio World Wide Web.
Esto da como resultado estandares acordados con capacidades que solo funcionan porque los navegadores web los implementan

Que es css
En primer lugar, diseñar e css es dificil
todavia se siente con ganas de hacer cossas basicas, como mostar algo en el medio absoluto de una pagina, siempre independientemente del tabaño de la
pantalla o del objeto, tal como ves que ve
Esto es asombroso Es el texto que quizas haya visto en algunas tazas de te
CSS es dificil
Echemos un vistazo como funciona

supongamos que quiero pintar con azul las letras de una lista

<div style="color:blue">
<li style="font-style:italic">is an</li>
</div>
tambien podemos declarar como una etiqueta
<style>
div {
colo: blue	
}
.italic {
	font-style: italic
}
</style>

hacerlo en forma de etiquetas es mas reutilizable
para vincular una hoja de estilo a un archivo css que contiene estos estilos
cuando el navegador carga el html tambien carga este archivo css y usa los estilos en el HTML haciendo que el color en el azul diff
El uso de css como este en archivos de hoja de estilo externos proporciona la maxima capacidad de mantenimiento y reutilizacion
En primer lugar, los estilos ya no estan en el documento HTML, lo que hace que todo sea mas facil de leer y mantener
Tambien proque los estilos estan en un documento separado
Puedo vincular ese documento en
multiples documentos html y aplicar los mismos estilos con la maxima reutilizacion, lo qeu da como resultado qeu los estilos se apliquen a ambas paginas web cuado el navegador los pinte
Como vimo, css consiste en propiedades y atributos como el color que se esta utlizando. azul o el texto es metalico y, como habras notado, ya nos ve puede indicar a qeu elemento se debe aplicar la propiedad.
Esto se hace con los llamados selectores como este que

<style>
div {
	color: blue;
}
</style>

selecciona todos los elementos de diferencias en una pagina HTML
o este que selecciona todos los elementos que tienen un atributo de clase A establecido en la clase uno
´´´css
.class {
color: blue;
}
´´´
Y existe este selector que selecciona todos los elementos en una pagina HTML qeu tienen un ID.
Fuera de la era uno

<style>
#para1 {
	color : blue;
}
</style>

Tambien puedes anidar cosas como esta

<style>
div p {
	text-align: center;
	color: red;
}
</style>

Este selecto selecciona todos los elementos de parrafo que tienen un elemento diff como padre

y este selecciona multiples elementos

<style>
h1, h2, p {
	text-align: center;
	color: red;
}
</style>

En la pagina HTML
Selecciona todos los encabezados de un ecabezado a los elementos de parrafo de
Estos son algunos de los selectores css
Hay muchos mas selectores qeu puede usar en css para seleccionar elementos en HTML y aplicar propiedades
El CSS del estudiante se denomina cascada en cascada como las hojas de estilo en cascada porque las propiedad es se aplican en un orden especifico en funcion de la prioridad
Considerado este HTML a los elementos de parrafo con mensajes de texto
Ambos tienen asignados especificos

<p class="specific">Paragraph.</p>
<p class="specific" id="morespecific">Paragraph with id!</p>

de clase y no de ellos tiene un Id off
mas especifico. Ahora aplicamos estas CSS al correo HC que da como resultado esta pagina webque da como resultado esta

<style>

#morespecific {
	background: red;
	border: 1px solid black;
	}
.specific{
	background-color: gray;
	border: none !important;
}
p {
	background-color: blue;
	color: white;
	padding: 5px;
}
</style>

lo que sucede aqui es que el selector de parrafo en la
el atributo de la clase (selectores)
class="especific"
tienen mas prioridad que los atributos de elemento

y que id selector tiene mas prioridad que las clases
y !important hace que el selector de clase sea mas importante que el id
y esto es lo que hace css ser dificil de leer y mantener

Advanced CSS Syntax
tambien hay capacidades mas avanzadas, que se pueden encontrar en las propiedades mas nuevas de css
una de ellas es la propiedad de consulta de medio (media query)
En este

<style>
@media screen and (min-width: 480px){
body {
	background-color: lightgreen;
}
}
</style>

yo le digo al browser que cuando vea @media_screen imprima una pagina
cuando la pantalla tiene un minimo de 480px
quiero que el elemento body tenga color de fonde verde
ESTO da como resultado que cuando maximizamos el navegador cambie su color a verde
y cuando amplio al minio se coloque en banco
Esto es lo que llamamos una pagina web responsiva (receptiva y responde al cambio, se ajusta en consecuencia)
Esto le permite tener un aspecto diferente en pantallas grandes y pequeñas (como en dispositivos moviles)

Otra propiedad avanzadas es el uso de gradientes

<style>
#grad{
	background: linear-gradient(red, yellow);
}
</style>

con html los navegadores web son los que proporcionan las capacidades reales
css solo le especifica el standar de lo que deben hacer cuando interpreta una determinada propiedad
Y al igual que con HTML, no todos los navegadores ofrecen el mismo soporte para todos los que ven esta propiedad
Hoy en dia, la mayoria de los anvegadores admiten la mayoria de los estandares css
pero no todo en el sitio web

#Working with CSS
como puedes crearlo
la web consta de de 2 documentos
documentos HTML que opcionalmente se puede diseñar con documentos css
Los documentos HTML y CSS viven en un servidor web en alguna parte
y se identifican mediante URL unicas. HTML y css pueden vivir en un mismo servidor
URL: http://serve.com/document1.html
URL: http://serve.com/stylesheet.css

o en diferentes servidores web, no importa, ya que puede vincular cualquier documento desde un documento html
estos documentos luego son transportado a traves del protocolo HTTP
que los envia a los navegadores web que los solicitaron en las computadoras de los clientes.
Para trabajar con css, todo lo que necesitamos saber es como acoplar CSS a HTML

otra cosa que hay que tener en cuenta es que el navegador web lo hace todo

#CSS Libraries

Otra forma de usar CSS es usar una libreria
Estos son archivos en css escritos por otras personas que ya
contiene muchos estilos que puede usar en
su documento de html
hay muchas bibliotecas de css disponibles
son de codigo abierto y gratuitas
Algunos contienen solo estilos css, otros contienen muchas mas cosas como archivos
como javascript, imagenes y mas
El mas popular es Bootstrap, creada por twitter
Otra es Hamburguesas.css
font Awesome, Ionic y materialice
Cada uno de estos proporciona diferentes estilos y capacidades diferentes
y todos estos estan diseñados para facilitarle la vida, ya que no tiene que crear los estilos, solo los usa
Veamos como puedes usar bootstrap como ejemplo
Para que bootstrap este vinculado a su HTML, podria
apuntar a uan URL como esta. Esta URL aunta a un archivo css bootstrap, que esta alojado en un servidor CDN
por lo que el servidor de otra persona utiliza una url como esta, no tiene que estar preocupandoce por alojar el archivo css
Su propio servidor web, pero debe tener en cuenta que este servidor que no controla a veces no puede estar disponible
De todos modos, una vez que tenga el archivo css puede comenzar a usar los estilos de bootstrap
bootstrap puede ayudarlo hacer mas rapido PERO debe aprender a como usarlo
Cuale son los diferentes stilos, como se llaman y que hacen

tambien tiene la opcion de utlizar preprocesadores de css
Un preprocesador css es un framework o lenguaje que se usa para crear estilos css
Los preprocesadores css pueden hacer cosas mas avanzadas que css
Se crearon porque algunas personas no estan conectadas con las expressiones simplistas que se pueden hacer en css y como esto puede llevar a documentos css grandes y difiles de mantener
hay muchos preprocesadores de css, como sass y less. Cuando utiliza un preprocesador css, escribe su codigo de estilo en el idioma del proprocesador
el lenguaje del less es mas avanzado que css
en el caso de less tiene caracteristicas como variables
Esto puede ser muy util
less se compila a css
los proprocesadores pueden aumentar tu productividad

Css es el mecanismo de diseno web
es un estandar que describe los selectore para seleccionar, propiedades y atributos
cada navegador interpreta el css a su manera
Afortunadamente segun los estandares 
css es util para separar el estilo del contenido
donde el css se describe en documentos css y el contenido en html
css es un estandar rico que describe muchas capacidades 
css provee de muchas propiedades avanzadas
mediaquerys
animaciones
degradados
y css esta evolucionando para incluir cada vez mas
capacidades que facilitan el estilo del contenido para dispositivos moviles y la creacon de animaciones
hay diferentes formas de usar css
de cero 
con librerias
con preprocesadores
