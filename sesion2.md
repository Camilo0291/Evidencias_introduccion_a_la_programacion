<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

# index.html
<img src= "https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/index.png?alt=media&token=a57fdad0-bd33-4351-843b-df2bcf396034"  width="600" height="600">

# about.html
<img src= "https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/about.png?alt=media&token=176e97d1-fc87-4bcc-ad6b-e6a6bd4f45fe"  width="600" height="600">

# contact.html
<img src= "https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/conta.png?alt=media&token=04451aac-79d8-4f80-b7a2-37c07ad610bc"  width="600" height="600">


# Solución: 

### Inicio
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer sitio web</title>
</head>

<body>

    <header>
        <font color="red">
            <h1>La creatividad en un código</h1>
        </font>
    </header>

    <nav>
        <lu>
            <li>
        </lu><a href="about.html">Acerca</a></li>
        <li><a href="contact.html">Contacto</a></li>
        </lu>

    </nav>

    <main>
        <p><strong>Bienvenid@s a mi sitio web en relación al software para que interactúes y te diviertas.</strong></p>
        <p>Aqui encontrarás una variedad de recursos utiles e información, para aprender y mejorar tus habilidades de
            desarrollo.<br>También me aseguraré de mantener este sitio actualizado con las últimas tendencias del mundo
            de la programación.</p>
    </main>

    <footer>
        <p>acquintanam@gmail.com</p>
        <p>Copyright 2023 - Camilo Quintana</p>
    </footer>

</body>

</html>
```

### Acerca
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head>

<body>

    <header>
        <font color="red">
            <h1>Sobre mí</h1>
        </font>
    </header>

    <p>Hola a todos</p>

    <p>Estoy emocionado de presentarles mi primera página web personal! Aquí podrán encontrar toda la información sobre
        mí y mi pasión por el mundo del software.
        Siempre he tenido un gran interés por la tecnología y el desarrollo de software. En esta página, compartiré con
        ustedes mi experiencia, proyectos y logros en este apasionante campo.
        Podrán conocer más sobre mi formación académica, habilidades técnicas y certificaciones. También encontrarán una
        sección dedicada a proyectos destacados en los que he trabajado, con detalles sobre las tecnologías utilizadas y
        los resultados alcanzados.
        Además, podrán contactarme a través de esta página para cualquier consulta, colaboración o propuesta que deseen
        hacerme. Estoy abierto a nuevas oportunidades y a trabajar en proyectos interesantes.
        A medida que siga avanzando en mi carrera y desarrollando nuevas habilidades, iré actualizando esta página con
        los últimos logros y proyectos en los que esté involucrado.
        ¡Espero que disfruten navegando por mi página web y descubriendo más sobre mi persona y mis aventuras en el
        mundo del software!
        ¡Gracias por visitar y nos vemos en la web!

        [Camilo Quintana]</p>

    <section>

        <article>
            <h3>Misión y Visión</h3>

            <p>Mi misión es ayudar a los clientes a lograr sus objetivos digitales a través del desarrollo de software
                de alta calidad y soluciones tecnológicas innovadoras.<br>Me comprometo a trabajar en estrecha
                colaboración con nuestros clientes para entender sus necesidades y brindarles un servicio personalizado
                y adaptado a sus requerimientos.</p>
        </article>

    </section>

    <nav>

        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="contact.html">Contacto</a></li>
        </ul>

    </nav>

    <footer>
        <p>Copyright 2023 - Camilo Quintana</p>
    </footer>

</body>

</html>
```

### Contacto
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>

<body>
    <header>
        <font color="red">
            <h1>Contacto</h1>
        </font>
    </header>


    <main>

        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre"><br>


            <label for="email">Email:</label>
            <input type="email" id="email"><br>


            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje"></textarea><br>


            <input type="submit" value="Enviar">
        </form>

        <aside>
            <h3>Ubicación</h3>
            <p>Calle 35 # 33 - 09</p>
        </aside>

    </main>

    <nav>
        <ul></ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="about.html">Acerca</a></li>
        </ul>
    </nav>

    <footer>
        <p>Copyright 2023 - Camilo Quintana</p>
    </footer>


</body>

</html>
```






