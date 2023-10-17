<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->


# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

# Solución:

```html
<!DOCTYPE html>
<html>

<head>
    <style>
        body {
            width: 100%;
            height: 100vh;
            margin: 0;
            padding: 0;
        }

        h1 {
            width: 50%;
            height: 150px;
            margin: 20px auto;
            padding: 30px;
        }

        p {
            float: left;
            width: 60%;
            height: 150px;
            margin: 20px;
            padding: 30px;
        }


        body {
            color: #000;
            background-color: #ac9fda;
        }

        h1 {
            color: #721a1a;
            background-color: #000;
        }

        p {
            background-image: url("image.jpg");
            background-repeat: initial;
            background-position: center;
        }


        body {
            font-family: Arial;
            font-size: 16px;
        }

        h1 {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 24px;
            font-weight: bold;
        }

        p {
            font-style: italic;
            font-variant: small-caps;
        }


        h1 {
            text-align: center;
        }

        p {
            text-align: justify;
        }


        body {
            border: 1px solid black;
        }

        h1 {
            border-width: 2px;
            border-style: dashed;
            border-color: red;
        }

        p {
            border-radius: 20px;
        }


        a {
            color: blue;
        }

        a:link {
            background-color: red;
        }

        a:active {
            background-color: green;
        }

        p:hover {
            background-color: gray;
        }

        button {
            cursor: pointer;
            background-color: blue;
        }

        button:active {
            background-color: red;
        }

        button:disabled {
            cursor: not-allowed;
            background-color: gray;
        }


        p::first-line {
            font-weight: bold;
            color: red;
        }

        p::first-letter {
            font-weight: bold;
            color: crimson;
            font-size: 80px;
        }

        p::after {
            content: "→";
            font-size: 30px;
            position: absolute;
            bottom: 0;
            right: 0;
        }

        h1::before {
            content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
        }
    </style>
</head>

<body>
    <h1>Este es un encabezado</h1>
    <p>
        Este es un párrafo de ejemplo y ensayo.
    </p>
    <a href="#">Enlace</a>
    <button>Botón</button>
</body>

</html>
```



