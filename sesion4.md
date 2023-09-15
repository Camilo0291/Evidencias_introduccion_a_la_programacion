<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

#Actividad: Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

<img src= "https://firebasestorage.googleapis.com/v0/b/foto-de-git.appspot.com/o/cuadro.png?alt=media&token=a1beb8fb-601b-4499-a895-5781a7b076dc">

# Solución:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>
    <table border="1" cellpadding="5" cellspacing="10">
        <thead>
            <tr>
                <th colspan="5">Automóviles Japoneses</th>
            </tr>
            <tr>
                <th>Código</th>
                <th>Nombre</th>
                <th>Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>

        </thead>
        <tbody>
            <tr>
                <td rowspan="2">0001</td>
                <td rowspan="2">Mazda MX5</td>
                <td>Es un automóvil SUV del segmento C que la marca japonesa Mazda lanzó al mercado a principios de
                    2012. En 2018 se renovó por completo, dando paso a la segunda generación del modelo. Tiene cinco
                    plazas, carrocería de cinco puertas, motor delantero transversal y tracción delantera o a las cuatro
                    ruedas.</td>
                <td>158.000.000 COP</td>
                <td>4</td>
                <td>20 de septiembre de 1989</td>
            </tr>
            <td>Te da la opción de lucir una capota en color negro o café.</td>
        <tbody>
            <tr>
                <td rowspan="2">0002</td>
                <td rowspan="2">Suzuki Jimy</td>
                <td>El Suzuki Jimny/Chevrolet Samurai para el mercado colombiano, Chevrolet Jimny para Venezuela, Suzuki
                    Samurai para Europa y América también conocido en España como Suzuki Santana por ser fabricado y
                    ensamblado en la planta de Linares, y como Chevrolet Samuraí al ser ensamblado en la planta de
                    Bogotá de GM, es un automóvil todoterreno pequeño producido por el fabricante japonés Suzuki.</td>
                <td>134.000.000 COP</td>
                <td>12</td>
                <td>10 de abril de 1981</td>
            </tr>
            <td>Tiene una gama de pinturas con los colores negro perla, verde selva, blanco o gris medio.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0003</td>
                <td rowspan="2">Toyota Corolla 2013</td>
                <td>Es un automóvil del segmento C producido por el fabricante japonés de automóviles Toyota desde el
                    año 1966. En 1997, el Corolla se convirtió en el automóvil más vendido del mundo, desplazando de
                    dicho sitial al Volkswagen Escarabajo, superando en la actualidad las 50 millones de unidades
                    vendidas
                </td>
                <td>58.500.000 COP</td>
                <td>15</td>
                <td>28 de marzo de 2018</td>
            </tr>
            <td>Un total de 203 tonos aparecieron en este auto.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0004</td>
                <td rowspan="2">Honda NSX</td>
                <td>El NSX fue el primer coche de producción que se construyó con un chasis monocasco hecho totalmente
                    en aluminio. Con una dirección asistida totalmente electrónica, un sistema electrónico de control
                    Drive-by-wire para la mariposa de admisión, un motor con bloque y culatas de aleación de aluminio
                    ligera, con las bielas de titanio, que puede alcanzar las 8000 rpm. Se le conocía como el "anti
                    Ferrari" debido a la rivalidad con la marca italiana, sin haber llegado
                    a tener un duelo entre modelos.</td>
                <td>61.500.000 COP</td>
                <td>10</td>
                <td>1999-2005</td>
            </tr>
            <td>Tiene un total de 30 tonos espetaculares.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0005</td>
                <td rowspan="2">Mazda RX-7</td>
                <td>El Mazda RX-7 es un automóvil deportivo producido por el fabricante japonés Mazda Motor Corporation
                    (マツダ株式会社 Matsuda Kabushiki-gaisha?) entre los años 1978 y 2002. Rivalizaba con otros deportivos
                    asequibles, como el Toyota Supra, el Honda NSX, la línea Nissan Fairlady Z y el Nissan Skyline.
                    El RX-7 era un reemplazo directo para el Mazda RX-4 y todos los deportivos con motor Wankel de la
                    gama de Mazda, con excepción del Mazda Cosmo.</td>
                <td>180.981.000 COP</td>
                <td>7</td>
                <td>1978-2002</td>
            </tr>
            <td>Cada una de las variaciones tiene unas peculiaridades diferentes para adaptarse a todo genero de
                conductores.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0006</td>
                <td rowspan="2">Toyota Supra</td>
                <td>Es un automóvil deportivo hatchback de 3 puertas con motor delantero montado longitudinalmente de
                    tracción trasera, producido por el fabricante japonés Toyota desde 1978 hasta la actualidad. Hubo
                    una
                    pausa desde 2002 hasta su reinicio en 2019.</td>
                <td>304.579.000 COP</td>
                <td>3</td>
                <td>1978-2002-2019 y presente</td>
            </tr>
            <td>Desplegó todas sus capacidades visuales para ofrecer una paleta de once colores distints, que van desde
                tonos bien convencionales y de bajo perfil hasta colores chillones y llamativos.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0007</td>
                <td rowspan="2">Nissan Datsun 240z</td>
                <td>El vendido en Japón como el Nissan Fairlady Z y conocido en otros mercados como el Nissan S30,
                    Nissan Z29 o Datsun 240Z y después como el 260Z y 280Z, fue el primer automóvil deportivo de la
                    serie Z de dos asientos, producido por el fabricante japonés Nissan Motor Company, desde 1969 hasta
                    1978. Fue diseñado por un equipo liderado por Yoshihiko Matsuo, la cabeza de los Estudios de Diseño
                    de Estilos de Autos Deportivos. HLS30 fue la designación del modelo con volante a la izquierda y
                    HS30 para el de mano derecha, también disponible con volante derecho.</td>
                <td>129.900.000 COP</td>
                <td>10</td>
                <td>1969</td>
            </tr>
            <td>Lo puedes encontrar de color rojo, negro, azul, verde, cafe, entre otros..</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0008</td>
                <td rowspan="2">Honda Civic Type-R</td>
                <td>Es una versión de automóvil deportivo más radical del Honda Civic, producido por el fabricante
                    japonés Honda Motor Co., Ltd. desde 1997. Cuenta con una carrocería más ligera y rígida,
                    motorización especialmente modificada, mejores frenos y chasis. También se utiliza el color rojo en
                    el interior para darle una distinción deportiva especial y para separarlo de otros modelos de Honda.
                    En Japón, una serie de diseño de coches Type R, se preparó para competir en un campeonato para
                    muchos aspirantes a pilotos de carreras.</td>
                <td>238.366.000 COP</td>
                <td>10</td>
                <td>1997-presente</td>
            </tr>
            <td>Por el momento tiene dos colores: rojo rally y blanco platino, son una exclusividad por que se agotan
                muy rapido.</td>
        </tbody>
        <tbody>
            <tr>
                <td rowspan="2">0009</td>
                <td rowspan="2">Mitsubishi Lancer</td>
                <td>Se trata de un auto muy exitoso en todas sus versiones, durable, con una fiabilidad de enorme
                    reputación, sea en cupé o sedán, familiar, 3 y 5 puertas, por sus magníficas mecánicas, sus
                    características y cualidades en el mundo de Rallys, gozando de una gran popularidad y aceptación. Es
                    el mayor ganador del Rally Safari Kenia y uno de los mayores ganadores del mundial de Rallys, por su
                    reconocida robustez.</td>
                <td>35.000.000 COP</td>
                <td>20</td>
                <td>1973-2017</td>
            </tr>
            <td>Los colores de carrocería disponibles son cuatro: blanco perla, rojo rally, gris mercurio y azul octano.
            </td>
        </tbody>
        <tr>
            <td rowspan="2">0010</td>
            <td rowspan="2">Subaru Impreza</td>
            <td>El Subaru Impreza es un compacto, del segmento C, fabricado por Subaru desde 1992. Actualmente se
                comercializa la quinta generación, presentada en 2017 y actualizada en 2021, con el lanzamiento de la
                versión híbrida enchufable, que actualmente es la única disponible.</td>
            <td>105.940.000 COP</td>
            <td>6</td>
            <td>1992-presente</td>
        </tr>
        <td>Antes esa de color plateado y negro, ahora tiene un total de 118 colores </td>
        </tbody>
    </table>

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






