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
