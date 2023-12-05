# Pagina-web-Pedro-Rodr-guez
Nombre: Pedro.

Apellidos: Rodríguez López.

Curso: 1ºB.



La página web que he diseñado para la asignatura de fundamentos de la Ingenieria informática habla sobre el avión de pasajeros más grande del mundo. Para el desarrollo de esta página he buscado información en internet (especialmente en youtube) y también he pedido ayuda a alguno de mis compañeros. 


Descripción de mi página web.

Mi página contiene una página de inicio, una página sobre mi, una página sobre el tema, una página de red, una página sobre esta asignatura y una página de contacto.


Página de Inicio. 

Para la página de Inicio he creado un documento denominado index.html. Desde la página de inicio puedes llegar al link de las demás páginas.

Para ello he utilizado la etiqueta <nav> que sirve para poder acceder a otra página. Dentro del nav he incluido el siguiente código:

 <ul>
                <li> <a href="html/sobremi.html">SOBRE MI</a></li>
                <li> <a href="html/tema.html">TEMA</a></li>
                <li> <a href="html/red.html">RED</a></li>
                <li> <a href="html/sobrefundamentosdeig.html">SOBRE LA ASIGNATURA</a></li>
                <li> <a href="html/contacto.html">CONTACTO</a></li>        
                
                
</ul>

La etiqueta <ul></ul> indica una lista que el orden no importa. 
La etiqueta <li></li> indica los elementos de la lista. 
La etiqueta <a></a> que crea un enlace para dirigirse a las demás páginas dentro de la misma página. 
Dentro de la etiqueta <a></a> hay que destacar el href para insertar el enlace de las otras páginas web. 

En la página de inicio para meterle el texto he utilizado la etiqueta <header> que sirve para introducir un texto introductorio.
Dentro del header hay un <h1></h1> que es el título <h2></h2> El subtítulo y el <p></p> donde hay una pequeña descripción.


Para darle diseño y color a la página he utilizado CSS para ello he creado un archivo dentro de la carpeta CSS denominada style.css. 
Para que los estilos CSS se pudiesen ver en mi página web he puesto debajo de la etique <title> el siguiente comando: 
<link rel="stylesheet" href=".\CSS\style.css"> Importante poner el punto que sirve para indicar la carpeta de los archivos CSS. 

Para poder darle color al texto he ayadido el class="" que sirve para indicar elementos especificos para luego editarlos en CSS. 

Con el CSS he puesto el fondo de un color utilizando blackgraund-color y lo he introducido dentro del .container. 

Para que se cambie de color rosa cada vez que te hacercas con el ratón al título de las otras paginas he utilizado el hover. 

Para cambiar el tipo de letra primero en el documento principal he puesto el link de el fondo que he utilizado y luego en CSS 
y he puesto el siguiente comando font-family: 'Share Tech', sans-serif; . 

Vídeo para hacer la página de inicio:

https://www.youtube.com/watch?v=ndD1zldnApU&t=365s&pp=ygUtY29tbyBoYWNlciB1bmEgcGFnaW5hIGRlIGluaWNpbyBlbiBodG1sIHkgY3Nz



Página Sobre mí


En la página sobre mi se encuentra una pequeña descripción sobre mí. Como se puede observar no hay ningún enlace a ninguna red social porque puede acceder gente desconocida. 

En esta parte de la página cuento porque he decidido estudiar ingeniería informática.

En los estilos CSS de esta página he añadido el @media que te permite editar la vista de la página. 

La línea rosa que está debajo del sobre mi la he creado con el siguiente código. 

.heading h1::after{
    content: "";
    position: absolute;
    width: 100%;
    height: 4px;
    display: block;
    margin: 0 auto;
    background-color: rgb(255, 33, 66);
}
Básicamente he creado un bloque en  la parte de abajo con CSS 


Para que el título este en el centro de la página he utilizado el aling-items: center; .


Para que el texto este alineado con las dos imagenes he utilizado la etiqueta justify-content: space-between. 

Para que las dos imágenes esten a la derecha he añadido el margin: right y el texto le he puesto un margin: 0 esto indica que el contenido se observará en la parte donde no haya ningún contenido. 

Vídeos que he visto para hacer la página sobre mi:

https://www.youtube.com/watch?v=Rqo_1TV7wQs&pp=ygUNYWJvdXQgbWUgcGFnZQ%3D%3D




Tema de la página.

En el tema de la página he hablado del avión de pasajeros más grande del mundo. He escojido este tema porque me gustan los aviones y especialmente este en concreto. Ya que me resulta impresionante que un objeto tan pesado pueda volar. 

Para el diseño de esta página no me he complicado mucho y he utilizado el mismo diseño de la página sobre mí pero he añadido un vídeo del primer vuelo del A380 con  la etiqueta <link></link>

También vi algunos vídeos para que las imágenes estén alineadas con el texto:

https://www.youtube.com/watch?v=mEMrFbX4Agg&t=28s&pp=ygUjaG93IHR1IHB1dCBpbWFnZXMgd2l0aCB0ZXh0IGluIGh0bWw%3D

https://www.youtube.com/watch?v=Q0KNxDpt71c&t=534s&pp=ygUjaG93IHR1IHB1dCBpbWFnZXMgd2l0aCB0ZXh0IGluIGh0bWw%3D

https://www.youtube.com/watch?v=lgX38fNbxmw&pp=ygUjaG93IHR1IHB1dCBpbWFnZXMgd2l0aCB0ZXh0IGluIGh0bWw%3D



Página de la Asignatura. 


En la página de la asignatura he puesto una introducción de la asignatura basándome en la guía docente y en el archivo de la descripción de la asignatura. 

Para el texto he utilizado la etiqueta <h1></h1> para el título  y la  etiqueta <p></p> para el texto introductorio.


Luego he creado un menú desplegable para poder ver las asignaturas que se han impartido en esta asignatura. 

Para ello he utilizado la etiqueta <select></select> y dentro del select he añadido el siguiente comando: 

<option selected
        class="selected">Bloque 1</option>
        <option>Tema 1: Antecedentes y perspectivas históricas</option>
        <option>Tema 2: El contexto actual de la informática</option>
        <option>Tema 3: La Ingeniería informática como profesión</option>

La etiqueta <option></option> he puesto los temas que se dan en los respectivos bloques. 

Con el CSS he añadido la etiqueta transform que te permite seleccionar los temas de la asignatura. 

También he utilizado un hover para que cada vez que pase con el cursor por el menu de selección el bloque resalte. 

Estos son algunos vídeos que he visto para poder hacer el menu de selección:

https://www.youtube.com/watch?v=59bhXBQL5m0&t=14s&pp=ygUfaG93IHRvIGRvIGEgc2VjdGlvbiBtZW51IGluIGNzcw%3D%3D

https://www.youtube.com/watch?v=R-1Hh--SrX0&t=112s

https://www.youtube.com/watch?v=OesmxT-kGSM&t=21s




Página de Red. 


Con la página red podrás acceder a las páginas de algunos compañeros he escojido estás tres páginas de mis compañeros porque los avatares que he utilizado se parecen a ellos especialmente la del medio. 

En esta parte lo principal ha sido el uso de CSS. 

La mezcla de colores que aparece al acercarte con el cursor a los perfiles la he hecho con la etiqueta background y dentro de background he añadido la siguiente función linear-gradient (el color 1, el color 2); 


Para el icono de github he usado una página web que tiene una gran variedad de iconos para poder poner en tu página web. La página web se llama Boxicons aquí tienes el enlace: https://boxicons.com/. 
Simplemente buscas el icono que quieres poner y copias su SVG y lo pegas en el documento html.
Luego el icono lo metes en un <div class'nombre del icono' para poder editarlo con CSS. 


Para los tres bloques he utilizado la etiqueta <section> y luego dentro del section he introducido varios <div> donde están incluidos las imágenes, los iconos de github y el nombre de mis compañeros. 


Para que las imagenes esten en forma circular, las he metido el pading y he utilizado border-radius: 50% 


Para el cambio de color cada vez que se pasa por los bloques he utilizado la etiqueta hover. Dentro del hover cabe destacar este comando: 
.card:hover .img-container {
    transform: scale(1.15);
Esto hace que la imagen se agrande y aparezca un borde que en mi caso es de color blanco. 

Tambíen para que desde la página web se pueda acceder a las otras páginas de mis compañeros pinchando en el icono. He introducido la imagen del icono dentro de la etiqueta <a> y luego he puesto el enlace de sus páginas con el href

Vídeos que he visto para hacer la página de red:






Página de Contacto. 

He incluido los elementos principales de un  formulario de contacto. Como el <imput></imput> que lo he utilizado para que se pueda escribir dentro de un bloque.
<textarea></textarea> te permite introducir más caracteres y lo he utilizado para que se pueda escribir tu opinión acerca de mi página web. Por último he creado un botón para que se pueda enviar el mensaje. 

 Con los estilos Css al botón le he metido un hover para darle un diseño al botón.






Problemas en el desarrollo de mi página web. 


El primer problema que tube al principio es que no sabía que poner en mi página web y de que tema podía hablar. En un principio hiba hablar de coches pero opte por la opción del avión porque es un tema que domino mejor que los coches. 

El segundo problema con el que me encontré fue que no tenía mucha idea del uso de html y Css (sobretodo de Css). Al final con la ayuda de algunos vídeos y del bootstrap pude seguir adelante. 


Una vez empezado la página web, los archivos Css no se me cargaban correctamente. El problema era que no había indicado correctamente la hubicación de la carpeta Css ya que yo puse en la etiqueta <link href"/CSS/sobremipagina.css"> y evidentemente no se me cargaban los archivos CSS porque hay que poner dos puntos antes de /, es decir para enlazar la pagina de css debería poner <link rel"" href"../CSS/...css"> para que funcionase. 


Otro problema que tuve es que no se me cargaban las imágenes por lo mismo que los archivos css (los dos puntos al principio). 

 A la hora de la publicación de mi página web tube varias dificultades con los repositorios github ya que tube que crear seis repositorios distintos. 

También no supe como subir mi pagina web a git hub a si que me miré un vídeo para poder subir mi página en github. Después descubrí que no era tan dificil. 
https://www.youtube.com/@GabrielCoding


Otro problema que tube es que no se me cargaban los cambios que hiba realizando en mi página web y descubrí que el problema era que no había vinculado git hub con el visual studio. 

Una vez vinculado visual studio code a mi página web los estilos css si me cargaban en chrome pero no me cargaban en Github porq no se me actualizaba los cambios. Para solucionar este problema accedí a mi página web desde el link que Git hub había creado para mi página web y presioné el f12 para inspeccionar los problemas y descubrí que en Git hub las carpetas de los archivos Css y las imágenes no estaban bien indicadas. Al final resolví este problema editando el código fuente y utilicé el comando git comit para indicar el cambio. 

Como se podrá observar otro de los problemas que me va a costar -0.5 puntos ha sido crear más de un archivo CSS, cuando en realidad sólo había que crear un archivo css con el nombre de estilos.css. Al darme cuenta de esto mi página web ya estaba muy avanzada y me resultó un trabajo tedioso introducir todos los archivos que había creado de CSS en un solo archivo, ya que esto implica cambio de etiquetas porque había repetido los nombres de muchas de las etiquetas. 



Conclusiones del Trabajo. 




























 



