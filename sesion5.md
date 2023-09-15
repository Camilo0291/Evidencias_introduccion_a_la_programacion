<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto
## Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

### Instrucciones:

1.Crear un nuevo documento HTML.
2.Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3.Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
4.Utilizar las etiquetas HTML apropiados para cada campo.

# Solución:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>

<body>
    <form action="">
        <header>
            <h1>
                <p>Formulario del pedido</p>
            </h1>
        </header>


        <label for="idnombre">Nombre del producto</label>
        <input type="text" name="nombre" id="nombre" placeholder="Ingrese el nombre del producto" size="30" required />
        </div>
        <br>
        <div>
            <label for="cantidad">Cantidad:</label>
            <input type="number" name="cantidad" id="cantidad" required />
        </div>
        <br>
        <div>
            <label for="precio_unitario">Precio unitario:</label>
            <input type="number" name="precio_unitario" id="precio_unitario" step="00.1" required />
        </div>
        <br>
        <div>
            <label for="precio_total">Precio total:</label>
            <input type="number" name="precio_total" id="precio_total" step="00.1" required />
        </div>
        <br>
        <div>
            <label for="direccion">Dirección de envío:</label>
            <input type="text" name="direccion" id="direccion" required />
        </div>
        <br>
        <div>
            <br>
            <div>

                <h1>Información de contacto</h1>

            </div>
            <br>
            <div>
                <label for="nombre_contacto">Información de contacto - Nombre:</label>
                <input type="text" name="nombre_contacto" id="nombre_contacto" required />
            </div>
            <br>
            <div>
                <label for="email">Información de contacto - Correo electrónico:</label>
                <input type="email" name="email" id="email" required />
            </div>
            <br>
            <div>
                <label for="telefono">Información de contacto - Número de contacto:</label>
                <input type="tel" name="telefono" id="telefono" required>
            </div>
            <br>
            <div>
                <label for="metodo_pago">Metodo de pago:</label>
                <select id="metodo_pago" name="metodo_pago" required>
                    <option value="tarjeta">Tarjeta de crédito</option>
                    <option value="transferencia">Transferencia bancaria</option>
                    <option value="efectivo">Efectivo</option>
                </select>
                <br>
            </div>
            <div>
                <label for="fecha_entrega">Fecha de entrega</label>
                <input type="date" name="fecha_entrega" id="fecha_entrega" required>

            </div>
            <br>
            <div>
                <label for="comentarios">Comentarios</label>
                <textarea name="comentarios" id="comentarios"></textarea>
            </div>
            <div>
                <input type="submit" value="Enviar">
            </div>

    </form>
</body>

</html>
```






