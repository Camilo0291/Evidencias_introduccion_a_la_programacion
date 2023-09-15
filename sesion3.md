<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
Utiliza encabezados para títulos en cada elemento `(<h1>...<h6>)`.

Crea una descripción para cada elemento utilizando párrafos `(<p>)`.

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

Usa `<strong>` para resaltar texto importante.
Utiliza `<br>` para insertar saltos de línea si es necesario.
Agrega `<span>` para aplicar estilos específicos a porciones de texto.
Emplea `<i>` para enfatizar o dar énfasis a palabras o frases.
Utiliza `<u>` para subrayar texto cuando sea necesario.
Considera el uso de `<div>` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Plantilla Inicial
```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```

## Semántica y Estructura de la Plantilla
El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

`<!DOCTYPE html>`: Esto define el tipo de documento como HTML5.

`<html>`: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

`<head>`: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque `<style>` para agregar reglas de estilo CSS.

`<title>`: Establece el título de la página en la pestaña del navegador.

`<style>`: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

`<body>`: Aquí se coloca el contenido principal visible de la página.

`<header>`: Sección de encabezado que contiene el título principal y un subtítulo.

`<h1> y <h3>`: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

`<section>`: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

`<h2>`: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

`<p>`: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

`<footer>`: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea <br> para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

- La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
- El encabezado `(<header>)` tiene un fondo oscuro, texto blanco y un espacio de relleno.
- Cada sección `(<section>)` tiene un borde, un espacio de relleno y un margen inferior.
- Los encabezados de nivel 1 y 3 están centrados.
- Los encabezados de nivel 2 `(<h2>)` tienen color azul.
- El pie de página `(<footer>)` tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.
Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.

# Solución:

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #3502ad;
            color: rgb(255, 255, 255);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        h3 {
            color: red;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h2><br>
            <FONT COLOR="white">Más fácil de agregar multimedia a tus sitios web</FONT></b>
        </h2>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p><strong>Algunas de las siete maravillas del mundo</strong></p>
        <u>
            <h3>El Cristo Redentor</h3>
        </u>
        <p>El Cristo Redentor o Cristo del Corcovado es una estatua art déco que representa a Jesús de Nazaret, con los
            brazos abiertos, mostrando a la ciudad de Río de Janeiro, Brasil. El Cristo Redentor es uno de los destinos
            turísticos más importantes de Brasil y uno de los lugares más visitados del mundo. Para algunos creyentes es
            también un lugar de peregrinación.
            <a href="https://es.wikipedia.org/wiki/Cristo_Redentor" target="_blank">Para más información</a>
        </p>
        <img src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Cristoredentor.jpg?alt=media&token=7a3f47ce-9abb-437e-8e8f-ca2192f6ebf7" width="600" height="600">
        <u>
            <h3>El Coliseo de Roma</h3>
        </u>
        <p>El Coliseo o Anfiteatro Flavio (en latín Colosseum, en italiano Colosseo) es un anfiteatro de la época del
            Imperio romano, construido en el siglo I. Está ubicado en el este del Foro Romano, y fue el más grande de
            los que se construyeron en el Imperio romano. <a href="https://es.wikipedia.org/wiki/Coliseo"
                target="_blank">Para más información</a>
        </p>
        <img src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/ColiseodeRoma.jpg?alt=media&token=892f5c4e-a775-4802-901b-b32faae33571" width="600" height="600">
        <u>
            <h3>La fachada principal de Petra</h3>
        </u>
        <p>Tesoro de Petra (en árabe: الخزنة, Al-Jazneh o Jazné) es la primera construcción de cierta entidad que
            encuentra el viajero cuando emerge del Siq, el desfiladero de 1.5 km que hay que recorrer para llegar a la
            ciudad escondida de Petra, en Jordania.El control de esta ruta comercial crucial entre las tierras altas de
            Jordania, el mar Rojo, Damasco y el sur de Arabia fue el elemento vital del reino nabateo y trajo a Petra su
            fortuna.<a href="https://es.wikipedia.org/wiki/Tesoro_de_Petra" target="_blank">Para más información</a>
        </p>
        <img src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/FachadadePetra.jpg?alt=media&token=12821e15-143b-4d4d-b5f4-accf050cbffb" width="600" height="600">
        <u>
            <h3>Parte de la Gran Muralla China</h3>
        </u>
        <p>La Gran Muralla china es una antigua fortificación china, construida y reconstruida entre el siglo v a. C.
            y el siglo xvi para proteger la frontera norte del Imperio chino durante las sucesivas dinastías imperiales
            de los ataques de los nómadas xiongnu de Mongolia y Manchuria. <a
                href="https://es.wikipedia.org/wiki/Gran_Muralla_China" target="_blank">Para más información</a>
        </p>
        <img src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Lagranmurallachina.jpg?alt=media&token=b965f798-fd91-4e0b-9176-27ccc5c81348" width="600" height="600">
    </section>


    <section>
        <h2>Videos relajantes</h2>
        <h3>Taj Mahal</h3>
        <p>Taj Mahal quiere decir "corona de los palacios" y es una de las siete maravillas del mundo. Fue construido
            entre 1631 y 1653 en Agra, la India. Se trata de un mausoleo dedicado a la esposa favorita del emperador
            Shah Jahan, llamada Arjumand Banu Begum, conocida como Mumtaz Mahal. <a
                href="https://www.culturagenial.com/es/taj-mahal/" target="_blank">Para más información</a>
        </p>
        <video src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/tajmahal_-_23592%20(360p).mp4?alt=media&token=66fb787f-3450-4bae-befb-745f6cf7fbaf" controls width="500"></video>


        <h3>Aurora Boreal</h3>
        <p>Las auroras boreales son un fenómeno atmosférico que se manifiesta con luces naturales en el cielo. Los
            colores típicos que se despliegan en él suelen ser azul, rojo, amarillo, verde y naranja. Estas ondulaciones
            luminosas son vistas, sobre todo, en las regiones polares bajas. <a
                href="https://www.ngenespanol.com/naturaleza/que-son-las-auroras-boreales-y-por-que-se-forman/"
                target="_blank">Para más información</a>
        </p>
        <video src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/aurora_borealis_-_90877%20(540p).mp4?alt=media&token=c54858cc-e13c-4229-a5c7-5c" controls width="500"></video>
    </section>

    <section>
        <h2>Audios naturales</h2>
        <ol>
            <li>Arroyo</li>
            <li>Viento</li>
            <li>Truenos</li>
            <li>Susurros</li>
        </ol>


        <h2><br>
            <FONT COLOR="red">Arroyo</FONT></b>
        </h2>
        <p>Este sonido puede tener diferentes formas, todo va depender de la persona que lo escucha y que le
         trasmite a sus sentidos, que pueden provocar tranquilidad o nostalgia.</p>
        <audio src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Arroyo.mp3?alt=media&token=b481efba-444e-4fab-ae98-450b1b3d979f" controls></audio>

        <h2><br>
            <FONT COLOR="red">Viento</FONT></b>
        </h2>
        <p>El sonido del viento se produce por algun obstaculo, ya que el aire se corta con rapidez y se divide
         cuando pasa por delante.</p>
        <audio src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Viento.mp3?alt=media&token=96325323-e813-4afa-a9a6-06049b1d5e71" controls></audio>

        <h2><br>
            <FONT COLOR="red">Truenos</FONT></b>
        </h2>
        <p>El sonido de los truenos puede transmitir miedo, estar en alerta, pero para la naturaleza es una
         sensación de alegria.</p>
            <audio src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Truenos.mp3?alt=media&token=8c86485c-bb86-44e8-a7f5-53592d5767fa" controls></audio>

        <h2><br>
            <FONT COLOR="red">Susurros en arbustos</FONT></b>
        </h2>
        <p>El ruido de los susurros puede ser un recurso de relajación y diferentes estados de animos o todo lo
         contrario puede ser ruidoso o molesto.</p>
            <audio src="https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/Susurros.mp3?alt=media&token=7d0e840d-e74f-43cb-b68d-91f453934e8f" controls></audio>


    </section>

    <section>
        <h1>iFrames</h1>
        <h3>Wikipedia</h3>

        <p>Con wikipedia puedes encontrar mucha información que te puede servir. <a
                href="https://es.wikipedia.org/wiki/Wikipedia:Portada" target="_blank">
                Para más información</a></p>
        <iframe src="https://es.wikipedia.org/wiki/Wikipedia:Portada" width="500" height="300"></iframe>

        <h3>Oceano Pacifico</h3>
        <p>Se presencia y se aprecia diferentes criaturas en el Oceano como lo son <strong><i> Cangrejos, Cachalotes,
         Camarones, Tiburones,Ballena jorobada. entre otros...</strong></i>
        </p>.</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/bB7GWtSQNaA" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
    </section>

    <footer>
        Andrés Camilo Quintana Montoya
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```







