Sitio ejemplo
Proyecto integrador inicial de Front End, porque permite ir descubriendo los conceptos progresivamente.
1. HTML
Primero pueden analizar:
<header>
<nav>
<main>
<section>
<article>
<footer>
y entender que HTML define la estructura semántica.
Después:
<a>
<img>
<h1>
<p>
<ul>
<li>
<form>
<input>
<textarea>
<button>

2. Los enlaces entre páginas
Esta parte es especialmente importante:
<a href="index.html">Inicio</a>
<a href="nosotros.html">Nosotros</a>
<a href="servicios.html">Servicios</a>
<a href="contacto.html">Contacto</a>
No existe una única página.
Tenemos:
index.html
    │
    ├── nosotros.html
    │
    ├── servicios.html
    │
    └── contacto.html
Y todas vuelven a enlazar con index.html.

3. CSS
Después pueden quitar temporalmente:
<link rel="stylesheet" href="css/estilos.css">
y abrir la página.
Van a ver inmediatamente la diferencia:
HTML = estructura
CSS = presentación

4. JavaScript
Finalmente pueden quitar:
<script src="js/script.js"></script>
y observar que:
el menú móvil deja de funcionar;
el formulario deja de mostrar el mensaje;
el resto de la página sigue funcionando.
Eso permite introducir una idea fundamental:
HTML estructura, CSS presenta y JavaScript agrega comportamiento.

Actividad
A transformar.
Por ejemplo:
Actividad 1: Cambiar el nombre NovaWeb por el nombre de su empresa..
Actividad 2: Cambiar los textos de las cuatro páginas..
Actividad 3: agregar una quinta página:
portfolio.html
y agregarla al menú.
Actividad 4: agregar imágenes.
Actividad 5: modificar los colores desde :root:
:root {
   --primario: #635bff;
   --primario-oscuro: #4d46d8;.
}
Actividad 6: agregar un nuevo servicio.
Actividad 7: modificar el formulario.
Actividad 8: agregar una validación JavaScript.
Actividad 9: crear una nueva función JavaScript.
Actividad 10: agregar el favicon.ico que está en el mismo directorio compartido
(Recomendado, crear una carpeta “assets” y agregar una etiqueta en head:
<link rel="icon" type="image/png" href="assets/favicon.png">
Actividad 11 subir todo a GitHub.
Y ahí ya tenés un proyecto que puede servir como puente perfecto para después introducir Git/GitHub → JavaScript → PHP → Laravel, porque empiezan a trabajar con una estructura real de proyecto y no solamente con archivos HTML aislados.
