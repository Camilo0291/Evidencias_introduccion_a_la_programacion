<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# Actividad: Propiedades de posicionamiento de CSS

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

- Crea un nuevo archivo HTML y CSS.
- En el archivo HTML, crea una estructura básica de página web con dos elementos div.
- En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

# Solución:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo HTML y CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Div 1</h1>
        <p>Este es el primer div.</p>
    </div>

    <div class="container">
        <h1>Div 2</h1>
        <p>Este es el segundo div.</p>
    </div>
</body>
</html>

```

```css
body {
    margin: 0;
    padding: 0;
}


.container {
    background-color: #f0f0f0;
    border: 1px solid #ccc;
    padding: 20px;
    margin: 10px;
    width: 300px;
    float: left;
}

.container h1 {
    font-size: 20px;
    margin: 0;
}

.container p {
    font-size: 16px;
    margin: 10px 0;
}
```
# Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?


# Solución:

1. position: relative mueve un elemento en relación con su posición normal en el flujo del documento, mientras que position: absolute posiciona un elemento en relación con un elemento contenedor que tiene una posición diferente de static o, si no hay ninguno, en relación con el elemento raíz del documento. Los elementos con position: absolute se eliminan del flujo normal del documento y no afectan la posición de otros elementos. La elección entre estos valores depende de tus necesidades de diseño y del comportamiento deseado para tus elementos.

2. Valores de z-index:

- La propiedad z-index toma un valor numérico, que puede ser positivo, negativo o cero. Cuanto mayor sea el valor, más arriba estará el elemento en el orden de apilamiento.
Orden de apilamiento:

- Los elementos con un valor de z-index más alto se colocarán encima de los elementos con un valor de z-index más bajo. Si dos elementos tienen el mismo valor de z-index, el orden de apilamiento se determina por el orden en el que aparecen en el HTML (el último en aparecer en el código HTML estará más arriba en el orden de apilamiento).
Aplicación de z-index:

- Para aplicar z-index, primero debes asegurarte de que el elemento esté posicionado (usando position: relative, position: absolute, o position: fixed).
Luego, simplemente agrega la propiedad z-index con el valor deseado al elemento que deseas controlar.

### Ejemplo de uso de z-index:

```html
<div class="element1">Elemento 1</div>
<div class="element2">Elemento 2</div>
```


```css
.element1 {
    position: relative;
    z-index: 2;
    background-color: red;
    width: 200px;
    height: 100px;
}

.element2 {
    position: relative;
    z-index: 1;
    background-color: blue;
    width: 200px;
    height: 100px;
}
```

En este ejemplo, element1 tendrá un z-index de 2 y, por lo tanto, se mostrará encima de element2, que tiene un z-index de 1. Si ambos tuvieran el mismo z-index, el orden de apilamiento se basaría en su orden en el código HTML.



3. La propiedad `display` en CSS se utiliza para controlar cómo se muestra un elemento en una página web. Cambiar el valor de `display` permite modificar el modelo de caja y el comportamiento del elemento. Aquí tienes algunos de los valores más comunes de `display` y su impacto en la visualización de elementos:

1.1. **`display: block`**:
   - Los elementos con esta propiedad ocuparán todo el ancho disponible y comenzarán en una nueva línea. Se extienden horizontalmente para llenar su contenedor y pueden tener márgenes y espacios tanto en horizontal como en vertical.

2.2. **`display: inline`**:
   - Los elementos con esta propiedad se muestran en la misma línea que el contenido que les rodea y solo ocupan el ancho necesario para su contenido. No permiten márgenes horizontales y espacios verticales.

3.3. **`display: inline-block`**:
   - Combina las características de `display: block` e `display: inline`. Los elementos ocupan solo el ancho necesario para su contenido, pero permiten márgenes y espacios tanto en horizontal como en vertical.

4.4. **`display: none`**:
   - Este valor oculta completamente el elemento, y no ocupará espacio en la página. Es como si el elemento no existiera en el código HTML.

5.5. **`display: flex`**:
   - Los elementos con esta propiedad se comportan como elementos flexibles dentro de su contenedor, lo que permite el diseño flexible y alineación de elementos hijos.

6.6. **`display: grid`**:
   - Los elementos con esta propiedad se comportan como elementos de cuadrícula, lo que permite la creación de diseños basados en cuadrícula y alineación de elementos en filas y columnas.

7.7. **`display: table`**, **`display: table-row`**, **`display: table-cell`**, etc.:
   - Estos valores simulan el comportamiento de una tabla HTML y se utilizan para crear diseños de tabla personalizados.

8.8. **`display: inline-flex`** y **`display: inline-grid`**:
   - Son variantes de `display: flex` y `display: grid`, respectivamente, que se muestran en línea con el contenido circundante.

9.9. **`display: initial`**:
   - Restablece el valor de `display` al valor predeterminado para el tipo de elemento. Por ejemplo, un `<div>` tendría `display: block` como valor predeterminado.

10.10. **`display: inherit`**:
    - Hereda el valor de `display` del elemento padre.

El valor de `display` se utiliza para controlar cómo se formatea y se muestra un elemento en el flujo de contenido. La elección del valor dependerá de tu diseño y requisitos específicos.







