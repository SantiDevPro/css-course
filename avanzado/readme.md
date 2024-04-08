# **CSS AVANZADO**

---

## _FILTER Y BACKDROP FILTER_

- `filter` | permite aplicar efectos de filtro a elementos HTML, como desenfoque, saturación, brillo, entre otros. Se utiliza para modificar la apariencia visual de un elemento sin modificar su contenido HTML subyacente

- Funciones para _filter_:

  - `blur()` | aplica un desenfoque gaussiano al elemento

  - `brightness()` | ajusta el brillo del elemento. Un valor de 0% resulta en un negro total, mientras que un valor de 100% deja el elemento sin cambios

  - `contrast()` | ajusta el contraste del elemento. Un valor de 0% resulta en un gris medio, mientras que un valor de 100% deja el elemento sin cambios

  - `drop-shadow()` | agrega una sombra al elemento, simulando la sombra proyectada por un objeto elevado sobre un fondo

  - `grayscale()` | convierte el elemento en una escala de grises. Un valor de 0% deja el elemento sin cambios, mientras que un valor de 100% lo convierte en una imagen en escala de grises completa

  - `hue-rotate()` | gira el matiz del elemento en un ángulo especificado. Se puede utilizar para cambiar los colores de un elemento

  - `invert()` | invierte los colores del elemento. Un valor de 0% deja el elemento sin cambios, mientras que un valor de 100% invierte completamente los colores

  - `opacity()` | ajusta la opacidad del elemento. Un valor de 0% hace que el elemento sea completamente transparente, mientras que un valor de 100% deja el elemento completamente opaco

  - `saturate()` | ajusta la saturación del elemento. Un valor de 0% produce una imagen en blanco y negro, mientras que un valor de 100% deja el elemento sin cambios

  - `sepia()` | aplica un tono sepia al elemento. Un valor de 0% deja el elemento sin cambios, mientras que un valor de 100% produce una imagen completamente sepia

- `backdrop-filter` | similar a la propiedad filter, pero se aplica al fondo detrás del elemento en lugar del elemento en sí. Se utiliza para aplicar efectos de filtro al fondo de un elemento, como desenfoque o cambio de color, creando así efectos visuales más complejos y sutiles

## _TRANSFORM_

- `transform` | se utiliza para aplicar transformaciones 2D y 3D a un elemento, como rotaciones, escalados, traslaciones y sesgos. Permite modificar la apariencia y la posición de un elemento sin alterar su diseño en el flujo del documento. Las transformaciones se aplican en relación con el origen del elemento y pueden ser animadas utilizando transiciones o animaciones

- Funciones para _transform_:

  - `rotate()` | rota un elemento en el plano 2D

  - `rotateX()` | rota un elemento en el eje X - 3D

  - `rotateY()` | rota un elemento en el eje Y - 3D

  - `rotateZ()` | rota un elemento en el plano 2D alrededor del eje Z

  - `scale()` | escala un elemento en el plano 2D en los ejes X e Y

  - `scaleX()` | escala un elemento en el eje X - 3D

  - `scaleY()` | escala un elemento en el eje Y - 3D

  - `scaleZ()` | escala un elemento en el eje Z - 3D

  - `translate()` | traslada un elemento en el plano 2D en los ejes X e Y

  - `translateX()` | traslada un elemento en el eje X - 3D

  - `translateY()` | traslada un elemento en el eje Y - 3D

  - `translateZ()` | traslada un elemento en el eje Z - 3D

  - `skew()` | sesga un elemento en el plano 2D en los ejes X e Y

  - `skewX()` | sesga un elemento en el eje X - 3D

  - `skewY()` | sesga un elemento en el eje Y - 3D

## _MIN, MAX Y CLAMP_

- `min` | retorna el menor de dos valores especificados

- `max` | retorna el mayor de dos valores especificados

- `clamp` | limita un valor dentro de un rango especificado, devolviendo el valor si está dentro del rango o el límite más cercano si está fuera de él. Sintaxis: _clamp(min-value,ideal-value,max-value)_

## _VARIABLES (custom properties)_

- Son valores definidos por el usuario que pueden reutilizarse a lo largo de un documento CSS

- Se definen utilizando la sintaxis _`--nombre-variable`_ y pueden contener cualquier valor válido en CSS, como colores, números, cadenas de texto, etc

- Las variables CSS proporcionan una manera eficiente de gestionar y reutilizar valores en estilos CSS, lo que facilita la creación de diseños más flexibles y mantenibles

## _FUNCION CALC_

- `calc()` | permite realizar cálculos matemáticos en línea para definir valores de propiedades CSS

- Con _`calc()`_, se pueden combinar valores numéricos con operadores matemáticos como suma, resta, multiplicación y división

- Esto proporciona una flexibilidad adicional para definir tamaños, posiciones y otros valores en CSS de manera dinámica y adaptable

## _PROPIEDADES DEL SCROLL_

- `scroll-behavior` | especifica el comportamiento de desplazamiento suave o instantáneo de un contenedor cuando el usuario navega por la página

- `scrollbar-color` | se utiliza para cambiar el color de la barra de desplazamiento de un contenedor. Permite especificar tanto el color del riel como el del mango de la barra de desplazamiento

- `scrollbar-width` | controla el ancho de la barra de desplazamiento de un contenedor. Permite establecer el ancho de la barra de desplazamiento para personalizar su apariencia

## _INITIAL LETTER_

- `initial-letter` | se utiliza para controlar el estilo visual de la primera letra o letras de un elemento, como un párrafo o una sección

- Permite especificar el tamaño, el estilo y otras propiedades de la primera letra, lo que puede ser útil para crear efectos decorativos o de diseño en el texto

## _UNIDADES DEL VIEWPORT (large, small y dynamic)_

- `UNIDADES DEL VIEWPORT` | son unidades de medida relativas al tamaño de la ventana gráfica del navegador

- Las unidades del viewport son: _`small viewport`_, _`large viewport`_ y _`dynamic viewport`_

- `small viewport (sv)` | representa el ancho y alto del viewport de dispositivos moviles o pequeños. El ancho es _small viewport width (svw)_ y el alto es _small viewport height (svh)_

- `large viewport (lv)` | representa el ancho y alto del viewport de ordenadores o dispositivos grandes. El ancho es _large viewport width (lvw)_ y el alto es _large viewport height (lvh)_

- `dynamic viewport (dv)` | representa el ancho y alto del viewport para dispositivos grandes y pequeños, tomando en cuenta los widgets o diferencias que hay entre pantallas de dispositivos moviles y ordenadores. El ancho es _dynamic viewport width (dvw)_ y el alto es _dynamic viewport height (dvh)_

## _MIN-CONTENT, MAX-CONTENT Y FIT-CONTENT_

- `min-content` | representa el tamaño mínimo necesario para contener el contenido sin que ocurra desbordamiento

- `max-content` | representa el tamaño máximo posible que el contenido puede ocupar sin que ocurra desbordamiento

- `fit-content` | representa el tamaño máximo posible que el contenido puede ocupar sin que ocurra desbordamiento, pero se ajusta automáticamente al tamaño mínimo necesario si el contenido es más pequeño que el contenedor

## _FUNCION COLOR MIX_

- `color-mix()` | permite mezclar dos colores según un porcentaje dado

## _CLIP PATH_

- `clip-path` | se utiliza para recortar un elemento mediante una forma definida, como un círculo, rectángulo o polígono

- Permite ocultar partes de un elemento y mostrar solo las áreas que están dentro de la forma especificada

- Esto puede ser útil para crear efectos de recorte personalizados en imágenes o elementos HTML

---
