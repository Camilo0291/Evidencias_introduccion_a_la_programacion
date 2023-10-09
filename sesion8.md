<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado `<header>`
- Tres párrafos `<p>`
- Una imagen `<img>`
- Un pie de página `<footer>`

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados `<h1>`
- Color azul a los párrafos `<p>`
- Borde grueso negro a la imagen `<img>`

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un `<div>`
- Centrar el contenido de la sección `<section>`

# Solución:

```html
<!DOCTYPE html>
<html>

<head>
    <style>
        header {
            color: red;
        }

        p {
            color: blue;
        }

        img {
            border: 3px solid black;
        }

        .destacado {
            color: green;
        }

        .grande {
            font-size: 24px;
        }

        #principal {
            color: yellow;
        }

        #sombras {
            box-shadow: 2px 2px 5px grey;
        }

        section p {
            color: grey;
        }

        section {
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Galería de imágenes</h1>
    </header>

    <p>La belleza de la naturaleza: Explora la majestuosidad de la naturaleza a través de esta colección de
        imágenes. Desde paisajes montañosos hasta playas de arena blanca, estas fotografías capturan la
        diversidad y
        la serenidad del mundo natural. Sumérgete en la tranquilidad de un bosque frondoso o déjate llevar por
        la
        inmensidad del océano. Cada imagen cuenta una historia única y te invita a explorar el mundo que nos
        rodea
    </p>
    <br>
    <p>La vida urbana en movimiento: Descubre la energía y la vitalidad de la vida en la ciudad a través de esta
        galería de imágenes. Desde rascacielos imponentes hasta calles llenas de gente, estas fotografías
        capturan
        la emoción y el ritmo acelerado de la vida urbana. Sumérgete en la multitud de una bulliciosa plaza o
        admira
        la arquitectura moderna de los edificios icónicos. Cada imagen te transportará a un mundo lleno de
        posibilidades y aventuras.
    </p>
    <br>
    <p>El arte en todas sus formas: Explora la creatividad y la expresión artística a través de esta galería de
        imágenes. Desde pinturas y esculturas hasta instalaciones y arte callejero, estas fotografías capturan
        la
        diversidad y la belleza del arte en todas sus formas. Sumérgete en los colores vibrantes de una obra
        maestra
        o descubre el significado oculto detrás de una instalación intrigante. Cada imagen te invita a
        reflexionar y
        a apreciar la creatividad humana.
    </p>
    <p class="grande">Este párrafo tiene un tamaño de fuente grande.</p>
    <img src="mostafa-meraji-vV_JB6LMTx4-unsplash.jpg" height="500" width="500" class="destacado">

    <section>
        <footer>
            <p> Andrés Camilo Quintana Montoya
                <br>
                <br>
                CESDE
                <br>
                <br>
                &copy;2023
            </p>
        </footer>
    </section>
</body>

</html>
```




