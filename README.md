# Practica-01---Mi-blog
//////////*Pasos a seguir en la creacion del Blog*\\\\\\\\\\

1. Use su editor HTML para abrir mp_index_txt.html, mp_menu.txt.html, mp_events_txt.html,
y archivos mp_catering_txt.html de la carpeta de revisión html01. Ingrese su nombre y la fecha
en la sección de comentarios de cada archivo y guárdelos como mp_index.html, mp_menu.html,
mp_events.html y mp_catering.html respectivamente.

2.Vaya al archivo mp_index.html en su editor HTML. Dentro del encabezado del documento, haga lo siguiente:
	a. Use el metaelemento para establecer la codificación de caracteres del archivo en utf-8.
		<meta charset="utf-8" />

	b. Agregue las siguientes palabras clave de búsqueda al documento: Italian, Mobile, Food y Charlotte.
		<meta name="keywords" content"Italian, Mobile, Food, Charlotte" /> 


	c. Establezca el título del documento en Mobile Panini.
		<title>Mobile Panini</title>


	d. Enlace el documento a los archivos de hoja de estilo mp_base.css y mp_layout.css.
		<link href="mp_base.css" rel="stylesheet" /> 
		<link href="mp_layout2.css" rel="stylesheet" />


3. Vaya al cuerpo del documento e inserte un elemento de encabezado que contenga lo siguiente:
	a. Una imagen en línea del archivo mp_logo.png con el texto alternativo Mobile Panini. marca el
	imagen como un enlace de hipertexto que apunta al archivo mp_index.html.
		<a href="mp_index_txt.html"><img src="mp_logo.png" alt="Mobile Panini" /></a>

	b. Una lista de navegación que contiene una lista desordenada con los siguientes elementos de la lista: Inicio, Menú,
	Eventos y Catering. Enlace los elementos a mp_index.html, mp_menu.html, mp_events.html,
	y archivos mp_catering.html respectivamente.
		<nav>
		<ul>
    		<li><a href="mp_index_txt.html">Index</a></li>
		<li><a href="mp_menu_txt.html">Menu</a></li>
		<li><a href="mp_events.html">Events</a></li>
		<li><a href="mp_catering.html">Catering</a></li>
		</ul>
		</nav>
	
4. Debajo del elemento de encabezado, inserte un elemento de artículo. Debajo del elemento del artículo, inserte un
elemento de pie de página que contiene el siguiente texto:
Mobile Panini 31 West Avenue, Charlotte NC 28204704-555-2188
  donde se inserta utilizando el código de caracteres 9832 y se agrega un espacio adicional entre NC y
28204 usando el nombre del personaje nbsp.
 	<footer>
 	Mobile Panini &#9832; 31 West Avenue, Charlotte NC &nbsp; 28204 &#9832; 704-555-2188
 	</footer>

5. Vaya al archivo mp_pages.txt en su editor de texto. Este archivo contiene el contenido de texto de los cuatro
páginas en el sitio web de Mobile Panini. Copie el texto de la sección de bienvenida, que se utilizará
en la página de inicio del sitio web. Regrese a mp_index.html en su editor HTML y pegue el
texto copiado en el elemento del artículo.


6. Dentro del elemento del artículo, haga lo siguiente:
	a. Marque la línea de bienvenida como un encabezado h1.
		<h1>Welcome</h1>

	b. Debajo del elemento h1, inserte una imagen en línea que contenga el archivo mp_photo1.png con un
	 cadena de texto vacía para el texto alternativo.
		 <img src="mp_photo1.png" alt=" " />
	
	c. Marque los siguientes cinco párrafos como párrafos usando el elemento p. Dentro del primer párrafo,
	 marque el texto Mobile Panini como texto fuerte. Dentro del tercer párrafo marque el texto
	 Curbside Thai como texto enfatizado.

	<p><Strong>Mobile Panini</Strong> is the culmination of the dream of
  	Antonio and Carmen Dolcini, who came to America 
  	looking to serve people the authentic recipes learned 
  	from their Sicilian family.</p>

	<p>Antonio began work as a child in his grandmother's 
	deli where he learned the age-old secrets of Sicilian 
	cooking. He refined his technique at the Culinary Institute 
	of Milan. His younger brother, Carmen, with no less of a love for 
	cooking and good food, also worked in the deli and became 
	well-acquainted with the open-air fresh food markets of his 
	home town. Carmen too, is a proud graduate of the Culinary Institute of Milan.</p>

	<p>Now you can enjoy what they have learned and mastered,
	right outside your door; but with no compromises in freshness 
	or delicacy of preparation. We've partnered with Curbside Thai to
	bring you the finest cuisine on four wheels - from the East and the West!</p>

	d. El cuarto párrafo contiene el número de teléfono de Mobile Panini. Marque el número de teléfono como
	 un enlace telefónico y asegúrese de incluir el código internacional en la URL. Tenga en cuenta que esto
	 el número es ficticio, por lo tanto, si tiene acceso a un navegador móvil y desea probar el enlace, usted
	 Es posible que desee reemplazar este número con su número de teléfono.
		 <p>Call: <a href="tel:0983364721">(07) 225-4778</a> </p>

	e. El quinto párrafo contiene la dirección de correo electrónico de Mobile Panini. Marcar la dirección de correo electrónico como
	 Un enlace de hipertexto. Una vez más, tenga en cuenta que esta dirección de correo electrónico es ficticia, por lo tanto, si desea
	 para probar este enlace, deberá reemplazar la dirección de correo electrónico de Mobile Panini con su
	 dirección de correo electrónico.
		<p>Email: <a href="mail:edwinM@ejemplo.com">edwinM@ejemplo.com</a></p>		


7. Guarde sus cambios en el archivo y luego abra el archivo mp_index.html en su navegador. Verificalo
El diseño y la apariencia de la página se parecen a los que se muestran en la Figura 1-45. Si es posible, pruebe el
enlaces telefónicos y correos electrónicos para verificar que abren la aplicación correcta.

8. Vaya al archivo mp_index.html en su editor HTML y copie el encabezado y pie de página
elementos. Luego vaya al archivo mp_menu.html en su editor HTML y pegue el encabezado
y elementos de pie de página en el elemento del cuerpo para que esta página tenga el mismo logotipo y
lista de navegación y pie de página utilizados en la página de inicio. Inserte un elemento de artículo entre el
encabezado y pié de página.

9. Regrese al archivo mp_pages.txt en su editor de texto y copie el contenido del Mobile Panini
menú. Luego, vaya al archivo mp_menu.html en su editor HTML y pegue el texto copiado en
el elemento del artículo.

10. Dentro del elemento del artículo del archivo mp_menu.htm, haga lo siguiente:
a. Marque el título del texto Nuestro menú como un encabezado h1.
si. Incluya los elementos del menú en una lista de descripción con el nombre de cada elemento del menú marcado con
el elemento dt y cada descripción de menú marcada con el elemento dd.

11. Guarde sus cambios en el archivo mp_menu.html. Abra la página en su navegador y verifique que cada
el nombre del elemento del menú aparece en negrita y está separado de la descripción del elemento sangrado por un
linea horizontal.

12. Vaya al archivo mp_index.html en su editor HTML y copie los elementos de encabezado y pie de página.
Luego, vaya al archivo mp_events.html en su editor HTML y pegue el encabezado y pie de página
elementos en el elemento del cuerpo. Insertar un elemento de artículo entre el encabezado y el pie de página.

13. Regrese al archivo mp_pages.txt en su editor de texto y copie la lista de próximos eventos en
Título de la sección del calendario. Luego, vaya al archivo mp_events.html en su editor HTML y pegue
El texto copiado en el elemento del artículo.

14. Dentro del elemento del artículo, haga lo siguiente:
	a. Marque el texto ¿Dónde estamos esta semana? como un encabezado h1.
	b. Incluya el valor de los eventos de cada día dentro de un elemento div (o división) separado.
	c. Dentro de cada una de las divisiones de siete días, incluya el día y la fecha como un encabezado h1. Encerrar
	 La ubicación dentro de un elemento de párrafo. Inserte un elemento de salto de línea, <br />, directamente
	 antes de la hora del evento para que cada intervalo de tiempo se muestre en una nueva línea dentro del
	 párrafo.
15. Guarde sus cambios en el archivo mp_events.html. Abra la página en su navegador y verifique que cada
El evento de calendario aparece en su propio cuadro con el día y la fecha representados como un encabezado.

16. Vaya al archivo mp_index.html en su editor HTML y copie los elementos de encabezado y pie de página.
Luego, vaya al archivo mp_catering.html en su editor HTML y pegue el encabezado y pie de página
elementos en el elemento del cuerpo. Inserte un elemento de artículo entre el encabezado y el pie de página y
luego inserte un elemento aparte dentro del artículo.

17. Directly after the opening <article> tag, insert an h1 element containing the text Catering.


18. Regrese al archivo mp_pages.txt en su editor de texto y copie el texto sobre la cocina móvil,
incluido el encabezado. Luego, vaya al archivo mp_catering.html en su editor HTML y pegue el
texto copiado en el elemento aparte.

19. Dentro del elemento del artículo, haga lo siguiente:
	a. Marque el texto Acerca de la cocina móvil como un encabezado h1.
	b. Marque los siguientes dos párrafos como párrafos.

20. Regrese al archivo mp_pages.txt en su editor de texto y copie el texto que describe Mobile Panini's
oportunidades de catering; No copie el cabezal de catering. Luego, vaya al archivo mp_catering.html en
su editor HTML y pegue el texto copiado directamente después del elemento aparte.

21. Realice las siguientes ediciones en el texto pegado:
	a. Marque los dos primeros párrafos como párrafos.
	b. Adjunte la lista de las seis posibilidades de catering dentro de una lista desordenada con cada elemento marcado
	 como un elemento de la lista.
	c. Marque el párrafo final como un párrafo.

22. Guarde sus cambios en el archivo mp_catering.html. Abra la página en su navegador y verifique que
La información sobre la cocina móvil aparece como una barra lateral en el borde derecho del artículo.

23. Regrese al archivo mp_index.html en su navegador y verifique que puede saltar de una página a
otro haciendo clic en las entradas en la lista de navegación en la parte superior de cada página.
 


