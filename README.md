
[![Netlify Status](https://api.netlify.com/api/v1/badges/cb42918c-7c9c-4528-98cc-b2e44661d6a4/deploy-status)](https://app.netlify.com/sites/miliga/deploys)
<h1>Descripción de miLiga.com Web</h1>
<h2>miLiga.com</h2> <p>WebV1.0. Este proyecto trata sobre un sitio web donde el usuario puede consultar datos actualizados tanto de la clasificación, resultados, proximos partidos y estadisticas, en la liga española y otras ligas.</p>

<p>Mediante unos menús de fácil comprensión, el usuario podrá consultar dichos datos, contando con filtros por equipos, jornadas y resultados para hacer una busqueda agradable.</p>



<h3>Si desea visitar el proyecto, pulsa <a href="https://miliga.com.netlify.app.">aqui</a></h3>

<h3>Funcionalidades</h3>
<p>*Visualización de la clasificación general de los equipos de la Primera división Española, donde el usuario podrá obtener la posición de su equipo así como los clasificados para las próximas competiciones europeas como son la Champions League, Europa League, UEFA Conference League, y los equipos en posición de descenso.</p> 
<p>*Visualización de todos los resultados de la Liga nacional, tanto los jugados como los que quedan por jugar. Además dispondrá de una función de fitrado por Partidos ganados, empatados y perdidos del equipo seleccionado, así como los proximos partidos a jugar. En dicha información observará tanto el numero de jornada, fecha y hora del encuentro, nombre y escudo de los equipos enfrentados y resultado obtenido.</p>
<p>*Visualización tanto del top 5 equipos con mejor promedio goleador, como del top 5 equipos menos goleados fuera de casa.</p>
<p>*Todos estos datos, no solo podemos mostrarlos de la liga española, sino que tambien disponemos de un desplegable con enlaces a otra ligas europeas, a las cuales se les aplicará los mismos filtros que a la liga principal</p>

<h3>Tecnologías  y leguajes empleados</h3>
<img src="/images/mix.jpg" alt="Tecnologias">

<h4>HTML5:</h4> <p>Utilizado para  montar el esqueleto de la web.</p>
<h4>CSS3:</h4> <p>Utilizado para dar pequeños ajustes en el diseño de la web.</p>
<h4>Bootstrap:</h4> </p>Utilizado en el grueso de la web para la realización del diseño y ajustes responsive.</p>
<h4>JavaScript:</h4> <p>Con el realizamos toda la parte dinamica y lógica de la web</p>
<h4>Postman:</h4> <p>Utilizada en un princiìo para recoger los datos a utilizar en la gestion de las tablas. Mas tarde se configuró con datos en linea mediante Fetch</p>
<h4>Git y GitHub:</h4> <P>Con ello trabajamos para la carga de los archivos componentes de la web a la nube.</p>
</br>
</br>
<h4>Descripción técnica:</h4>
<h3>En este proyecto utilizamos diversas funcionalidades agrupadas en dos tipos: Genéricas y Específicas, estas funcionalidades son las que utilizaremos  mediante Javascript.</h3>

<h4>Aqui tenemos algunas funcionalidades Genéricas: getFetch(),  matchTable(), spinnerOut().</h4>

<p>*getFetch(): Esta función es la encargada de recoger los datos desde la web proveedora de la información sin utilizar Postman y en estado dinámico, es decir actualizado constantemente.</p>
<p>*matchTable(): Ésta es la función encargada de crear las diferentes tablas que mostraremos en nuestro sitio web. Será ejecutada cuando, bien por carga de página con datos generales, o bien tras la eleccion mediante los diferentes inputs, elegimos que datos mostrar, tales como partidos ganados, perdidos o empatados, o tras seleccionar otras de las diferentes ligas con las que contamos para mostrar.</p>
<p>*spinnerOut(): Ésta es la llamada que utilizaremos tras cargar las diferentes tablas, para ocultar de pantalla el spinner que mostramos mientras se cargan las diferentes páginas de información mediante tablas.</p>
</br>
</br>
<h4>Aqui mostramos las funcionalidades algunas de las funcionalidades específicas:

<p>*limpiarTabla(): Con esta función, limpiamos el body de nuestra tabla para poder mostrar nueva información solicitada mediante nuestros inputs.
<p>filtrarEquipos(): Con ella, filtramos de nuestras arrays los equipos que cumplan las condiciones establecidas, para tras ello crear una nueva array con la que creremos nuestras tablas.
<p>filtrarJornada(): Misma función que la anterior, pero en este caso la utilizaremos para crear arrays por jornada introducida.</p>

<p>*staticsTable() y statics(): Funciones con las que filtramos y creamos las tablas de estadisticas del Top 5 equipos con mejor promedio goleador.</p>

<p>*staticsTable2() y statics2(): Funciones con las que filtramos y creamos las tablas de estadisticas del Top 5 equipos menos golados fuera de casa.</p>

<h3>Versiones</h3>
<p>*v1.0 (16.02.2022): Presentación proyecto.</p>

<h3>TO-DO</h3>
<p>Mejora de diseño</p>
<P>Añadir nuevas opciones de búsqueda para facilitar al usuario así como dar mas información, o de una manera mas práctica</p>
<p>Añadir secciones de noticis deportivas actualizadas</p>
