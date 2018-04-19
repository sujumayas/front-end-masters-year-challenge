# 01 Introduction to Web Development

This is a deep and comprehensive, “Get Started” course to give you the skills you need to be a professional web developer. Go from no prior coding knowledge to crafting your own websites using HTML, CSS, JavaScript, and node.js. Taught by Nina Zakharenko and Brian Holt, developers at Reddit!

**Link**: https://frontendmasters.com/courses/web-development/
**Published**: October 16, 2014

------

##1. INTRO > Tools & Documentation

	Lo básico : Sublime + Chrome
	Otra cosa que usaremos aquí: Codepen

	Documentación: 

	1. MDN  		https://developer.mozilla.org/es/ 
	2. CSSTricks 	https://css-tricks.com/
	
	No usar: W3Schools. 

##2. INTRO > Client & Server

	Aquí introducir este tema. El viaje del request. Algunos dibujos. 

##3. HTML > Hypertext Markup Language (HTML)

	HTML no es código. Es Markup (Es un lenguaje de Marcado.). Es importante entender que lo inventaron para archivar y enviar de forma ordenada y con un sólo código documentos académicos entre universidades. Finalmente, se empieza a usar para cosas mucho más complejas y hoy ya casi no queda nada de eso, pero así comenzó. 

	Se utiliza para definir la estructura de un documento (web) y es laa base de cualquier web. Será sobre este documento base que funcionarán los Estilos (CSS) y las funcionalidades más complejas agregadas con Javascript.

##4. HTML > My First Web Page

	Ejercicio de Codepen que muestra un poco lo que se puede hacer. H1, parrafos, explicar lo que pasa cuando no tienes tags por ejemplo. 

##5. HTML > Tags - Meta, Content
	
	```html
	<doctype>: solo algo que dice que tipo de documento usamos.
	<html>: encuadra todo el documento (casi)
	<head>: donde van todos los meta-tags y el Title de la página. 
	<body>: donde va todo el contenido de la web
	<h1>, <h2>, <h3>... <h6>: Títulos ordenados por prioridad.
	```
	
	Explicación de por qué solo hay 1 H1 por página: Aunque nosotros decidimos realmente usar la interpretación que querramos para organizar nuestros titulos, existe el SEO y los crawlers que definen lo que está bien y lo que está mal en una estructura web. Y hay que estar al tanto de esto para que todo salga bonis. 
	
	```html
	<p>: párrafos. 
	<span>: contenedor genérico de texto. 
	<div>: división de contenido. Usado para agrupar contenidos. 
	<ul>: lista desordenada
	<ol>: lista ordenada
	<li>: elemento de lista
	```

	Ejemplo sobre "hablarle a tu futuro yo y escribir html semántico aunque no veamos la diferencia entre listas ordenadas y desordenadas".

	Si no le pones un nombre correcto al tag y no usas el tag correcto, tendrás que revisar todo el contenido nuevamente y todo tu codigo para asegurarte de que era lo que creías cuando lo vuelvas a ver. 

	Otros Tags: 

	```html
	<br>: 
	<strong>: 
	<header>: 
	<footer>: 
	<main>: 
	<article>: 
	```

##6. HTML > Excercise 1: Creating a New Page

	1. Crear una página que tenga título
	2. Crear una lista desordenada con las cosas que te gustaría recibir en navidad.
	3. Crear una lista ordenada de tus canciones favoritas.
	4. Ponle un título a cada lista. 

##7. HTML > Excercise 1: Solution

	Revisar:

	(1) Sintaxis de Elementos
	(2) Indentación. La importancia de mantener la jerarquía aunque no parezca hacer nada evidente. 
	(3) No olvidar cerrar con los tags de cierre. 
	(4) ¿Agregamos el titlo + su lista en un div mejor? (Todo sea por el orden y el futuro reutilizable)

##8. HTML > Audience Questions

	Span vs Div
	Inline vs Block (ver: css)
	divs dentro de parrafos? Not valid HTML > Talk about validation. 
	

##9. HTML > Review

	Repasar algunos temas que se perdieron. 

	Por ejemplo, volviendo al tema de Semantic HTML: 
	
	```html
	<strong> no significa "negritas" si no "resaltado".
	<em> no significa italicas, significa que quieres darle emphasis.
	<span> significa que quieres separarlo del resto de cosas. :D
	```
##10. HTML > Tags - Void Tags

	```html
	<input>
	<img src="http://placekitten.com/400/400">
	```
	
	Y podemos hablar un poco sobre los atributos. 
##11. HTML > Tags - Grouping

	HTML es la estructura de tu documeto Html. Así que lo más importante es agrupar cosas :D
	Sobre todo cosas que se vayan a repetir, o que tengan un significado cerrado, o etc. 

	BEST PRACTICE: Agrupar todo lo que tenga sentido agrupar con un div. Se verá igual, pero el esfuerzo extra
	valdrá la pena! :D
##12. HTML > Classes

	Ok. Ahora veremos cómo ponerle un nombre a esos grupos que creamos antes. Ahora sí que se convierten en algo valioso. 
	
	```html
	<div class="media-object">
		<p>Parrafo 1</p>
		<img src="imagen1.jpg">
	</div>
	```
##13. HTML > ID's

	Los Ids funcionan igual que las clases pero con una gran diferencia: Son unicos. (O por lo menos deberían serlo!!)
	
	```html
	<div id="nombreUnico" class="media-object">
		<p>Parrafo 1</p>
		<img src="imagen1.jpg">
	</div>
	```
	Lo interesante es que puedes ponerle todas las clases que quieras a un elemento, pero solo 1 ID, y además el ID es único. 
	
	```html
	<div id="nombreUnico" class="media-object fondo-verde">
		<p>Parrafo 1</p>
		<img src="imagen1.jpg">
	</div>
	```
##14. HTML > Tags - Naming

	Going Back to Semantic Stuff. Aquí podemos incluir un poco de material sobre BEM. 
	Pero, en resumen es evitar nombrar las clases de forma "presentacional" como "right-navigation" y al mismo tiempo intentar que siempre los nobmres sean referenciales del contenido que muestran. Como "main-sidebar" o algo  así. 

	Menos "como se ve" y más "qué es". <3
##15. HTML > Excercise 2: Giving Classes

	Aquí hay que colocar un ejercicio (o más) de darle clases a elementos de HTML. 
##16. HTML > Excercise 2: Solution

	Aquí hacer un resumen de las soluciones de esos ejercicios. Y explicar algunos conceptos básicos como (1) como amplificar la funcionalidad básica del html con clases, es decir, a nivel de arquitectura. (2) como nombrar las cosas de forma que no tengamos que leer los contenidos - evitar cosas demasiado genéricas. (3) Como simplificar los nombres por secciones o areas o tipos de contenidos para que el CSS no sea tan complicado de escribir. 

	Otros temas que se pueden tocar: CamelCase vs . 
##17. CSS > What is CSS?

	Cascading Style Sheets. 

	Mientras el HTML es el código que define qué contenidos habrá en tu web, y cómo se estructuran; CSS decide cómo se verán estos contenidos en la web. 

	CSS es una colección de reglas que adjudicas a los distintos tipos de elementos del HTML seleccionandolos por medio selectores. Los selectores más básicos son : 


	```css
	p {
		/* Element Selector : Selecciona todos los párrafos de la página. */
	} 
	.red {
		/* Class Selector: Selecciona a todos los elementos que tengan esta clase. */
	} 	
	#someUniqueId {
		/*Id Selector: Selecciona todos los elementos que tengan este id. */
	} 
	```
##18. CSS > Better Practices

	**Aquí podemos colocar info de muchos lados.** 
	Cosas básicas:
		- Ponerle clase a todo. 
		- Evitar IDs 
		-   
##19. CSS > Text Properties and Measurements

	```css
	.text-propertys {
		color: red; /* Cambia el color del texto a rojo */
		font-weight: bold/900; /* Cambia el peso de las letras */ 
		font-style: italic; /* Cambia el estilo del texto a itálicas */
		text-align: center; /* Alinea el texto al centro */
		font-size: 25px; /* Cambia el tamaño del texto */
	}		
	```
##20. CSS > Boxes
##21. CSS > Box Questions
##22. CSS > Positioning 
##23. CSS > Shortcuts
##24. CSS > Order & Specificity
##25. CSS > Specificity Best Practices
##26. CSS > Resets and the Developer Tools
##27. CSS > Audience Questions
##28. CSS > Document Flow
##29. CSS > Float Tips
##30. CSS > Excercise 3: Styling a Page
##31. CSS > Excercise 3: Solution 
##32. CSS > Excercise 3: Final Questions 
##33. CSS > Conclusion
##34. JS > An Introduction to Programming
##35. JS > Excercise 4: Seeing Results
##36. JS > Variables, Variables Types & Reserved Words
##37. JS > Excercise 5: Writing Javascript
##38. JS > Operators, Expressions & Comparisons
##39. JS > Logical Operators & Arrays
##40. JS > Excercise 6: Arrays
##41. JS > Manipulating Arrays
##42. JS > If Statements
##43. JS > For Statements
##44. JS > Functions
##45. JS > Scope
##46. JS > Objects & Context
##47. JS > Objects & Context Questions
##48. JS > Anonymous Functions
##49. JS > Aditional Topics
##50. JQUERY > What is jQuery?
##51. JQUERY > jQuery Chaining
##52. JQUERY > Responding to Users
##53. JQUERY > Retrieving Text from an Input
##54. JQUERY > Exercise 8: Set Text
##55. JQUERY > Exercise 8: Solution
##56. JQUERY > Other DOM Functions
##57. JQUERY > jQuery and DOM Audience Questions
##58. AJAX > AJAX Introduction
##59. AJAX > Displaying Data
##60. AJAX > Exercise 9: Displaying Data from Reddit
##61. AJAX > Exercise 9: Solution
##62. AJAX > Troubleshooting
##63. COMMAND LINE > Introduction to the Command Line
##64. COMMAND LINE > Navigating with the Command Line
##65. COMMAND LINE > Git and Github
##66. COMMAND LINE > Git Status
##67. COMMAND LINE > Git Add, Commit, & Push
##68. COMMAND LINE > Cloning Review
##69. COMMAND LINE > Navigating Github.com
##70. COMMAND LINE > Pull Requests
##71. COMMAND LINE > Initializing a New Repository
##72. NODE.JS > Node.js Introduction
##73. NODE.JS > Node Package Manager
##74. NODE.JS > Express
##75. NODE.JS > Exercise 10: Cheer and Jeer
##76. NODE.JS > Static Assets
##77. NODE.JS > Receiving Parameters
##78. NODE.JS > Package.json
##79. NODE.JS > POSTing
##80. NODE.JS > Final Project - Client Side
##81. NODE.JS > Final Project - Server Side

