<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->


# Preguntas:

- ¿Qué es la propiedad margin?

- ¿Qué es la propiedad padding?

- ¿Qué es la propiedad border?

- ¿Qué es la propiedad border-radius?

- ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


# Solución:

1. Se utiliza para establecer el margen alrededor de un elemento HTML. El margen es el espacio blanco que se encuentra fuera del borde de un elemento y puede ser ajustado en los cuatro lados. Se puede especificar el valor del margen utilizando medidas, como pixeles (px), porcentajes (%) o ems (em).


2. Se usa para agregar espacio de relleno alrededor del contenido de un elemnto. El espacio de relleno se visualza como espacio transparente entre el contenido y los bordes del elemento. Puedes especificar diferentes valores de padding para cada lado de un elemento (arriba, derecha, abajo, izquierda) o puede establecer un valor unico que se aplicará a todos los lados.


3. Se utiliza para establecer el estilo, ancho y color del borde de un elemento. Puedes definir diferentes aspectos del borde, como su grosor, estilo (como solido, punteado, etc) y color. La sintaxis basica para la propiedad "border" es:

css
border: [ancho] [estilo] [color];


Donde:

- "ancho" especifica el grosor del borde en píxeles, puntos, porcentaje o palabras clave predefinidas como "thin", "medium" o "thick".
- "estilo" define la apariencia del borde, como "solid" (sólido), "dotted" (punteado), "dashed" (guiones), entre otros.
- "color" establece el color del borde, que puede ser un valor hexadecimal, un nombre de color o la palabra clave "transparent" para un borde invisible.

Por ejemplo, puedes utilizar la propiedad "border" de la siguiente manera:

css
border: 2px solid red;


Esto establecerá un borde de 2 píxeles de grosor, de estilo sólido y de color rojo alrededor de un elemento.


4. Se utiliza para especificar la curvatura de las esquinas de un elemento con bordes. Permite redondear las esquinas de un elemento creando esquinas suaves y curvas en lugar de esquinas afiladas. Puedes aplicar esta propiedad a elementos como cuadros, imágenes o cualquier elemento con bordes. Puedes definir un solo valor para todas las esquinas o valores individuales para cada una de ellas. Por ejemplo, `border-radius: 10px;` aplicaría un radio de curvatura de 10 píxeles a todas las esquinas del elemento.


5. 
- Píxeles (px): Es la unidad de medida más común y representa un valor absoluto en píxeles.

- Porcentaje (%): Permite especificar el espaciado relativo al tamaño del elemento contenedor.

- Em (em): Esta unidad de medida se basa en el tamaño de la fuente del elemento. Un em es igual al tamaño de la fuente actual.

- Rem (rem): Similar a la unidad `em`, pero se basa en el tamaño de la fuente del elemento raíz (`html`), lo que lo hace más predecible y fácil de usar.

- Centímetros (cm), milímetros (mm), pulgadas (in): Estas unidades de medida también se pueden utilizar, especialmente en casos donde se requiere un espaciado más preciso y basado en unidades físicas.

Estas son solo algunas de las unidades de medida comunes utilizadas en CSS para especificar el espaciado. La elección de la unidad dependerá del contexto y de tus necesidades específicas.



