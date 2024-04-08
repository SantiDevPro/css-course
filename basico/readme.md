# **CSS BASICO**

---

## _SELECTORES (básico)_

- Es la forma de seleccionar uno o varios elementos para estilar
- `*` | Selector Universal
- `etiqueta` | Selector de tipo
- `.class` | Selector de clase
- `#id` | Selector de ID
- `[atributo]` | Selector de atributo
- `etiqueta:pseudo-clase` | Selector de pseudo-clase

## _PROPIEDADES DE TEXTO Y FUENTE_

- `color` | propiedad para cambiar el color de fuente
- `font-family` | propiedad para cambiar el tipo de fuente
- `font-size` | propiedad para cambiar el tamaño de fuente
- `font-weight` | propiedad para cambiar el grosor de fuente
- `font-style` | propiedad para cambiar el estilo de fuente
- `text-align` | propiedad para alinear el texto en su contenedor
- `text-decoration` | propiedad para decorar el texto
- `text-transform` | propiedad para transformar la letra del texto
- `line-height` | propiedad para darle tamaño a las lineas de un texto
- `letter-spacing` | propiedad para darle separación a las letras de un texto

## _TIPOGRAFIAS EXTERNAS_

- Se puede vicular una tipografia externa con `<link>` y la `url` correspondiente
- La forma recomendada de vincular tipografia externa es configurandola con su correspondiente `url` y `@font-face`

## _MODELO DE CAJA (box model)_

<img src="../img/box-model.png">

- `width` | propiedad para definir el ancho de una caja o elemento
- `height` | propiedad para definir el alto de una caja o elemento

## _RELLENO Y MARGEN (margin y padding)_

- `margin` | propiedad para definir el espacio que habrá entre un elemento y los elementos que estén a su alrededor
- `margin-left` | propiedad para definir el espacio que habrá entre un elemento y los elementos que se encuentren a su izquierda
- `margin-top` | propiedad para definir el espacio que habrá entre un elemento y los elementos que se encuentren arriba
- `margin-right` | propiedad para definir el espacio que habrá entre un elemento y los elementos que se encuentren a su derecha
- `margin-bottom` | propiedad para definir el espacio que habrá entre un elemento y los elementos que se encuentren abajo
- `padding` | propiedad para definir el espacio que habrá entre el contenido y borde de un elemento
- `padding-left` | propiedad para definir el espacio que habrá entre el contenido y borde izquierdo de un elemento
- `padding-top` | propiedad para definir el espacio que habrá entre el contenido y borde superior de un elemento
- `padding-right` | propiedad para definir el espacio que habrá entre el contenido y borde derecho de un elemento
- `padding-bottom` | propiedad para definir el espacio que habrá entre el contenido y borde inferior de un elemento

## _BORDES_

- `border-width` | propiedad para definir el grosor del borde de un elemento
- `border-style` | propiedad para definir el estilo del borde de un elemento
- `border-color` | propiedad para definir el color del borde de un elemento
- `border` | propiedad para definir el grosor, estilo y color del borde de un elemento
- `border-left` | propiedad para definir el grosor, estilo y color del borde izquierdo de un elemento
- `border-top` | propiedad para definir el grosor, estilo y color del borde superior de un elemento
- `border-right` | propiedad para definir el grosor, estilo y color del borde derecho de un elemento
- `border-bottom` | propiedad para definir el grosor, estilo y color del borde inferior de un elemento
- `border-radius` | propiedad para redondear las esquinas del borde de un elemento

## _TAMAÑO DE CAJA (box sizing)_

- `box-sizing` | propiedad para afectar como funcionará el modelo de caja predeterminado
- `content-box` | modelo de caja predeterminado, que define el tamaño de caja solo para el contenido, haciendo que el relleno, margen y borde sean aparte, teniendo una caja con mayor dimensiones que al inicio
- `border-box` | modelo de caja más usado, que define el tamaño de caja tomando en cuenta el contenido, relleno y borde, dejando fuera solo al margen, teniendo una caja más fija en dimensiones

## _COLORES_

- _`RGB` | Red Green Blue_
  - Modelo cromático que representa distintos colores a partir de la mezcla de los colores rojo, verde y azul
  - Cada valor puede estar en el rango del 0 al 255
  - Sintaxis: `rgb(value-red, value-green, value-blue)`
- _`RGBA` | Red Green Blue Alpha_
  - Funciona igual que rgb pero agrega un cuarto valor el cual define la opacidad del color
  - Cada valor puede estar en el rango del 0 al 255, menos el Alpha que su rango es del 0 al 1
  - Sintaxis: `rgba(value-red, value-green, value-blue, value-alpha)`
- _`Colores Hexadecimales`_
  - Sistema de notación numérica utilizado para representar colores
  - Basado en los valores Red Green Blue pero en base numerica 16
  - Tiene dos sintaxis: `#RRGGBB` o `#RGB`
  - Los valores de cada cifra va del 1 al 9 y del A a la F
- _`Colores Hexadecimales + Alpha`_
  - Funciona igual que los colores hexadecimales pero se agrega el valor Alpha
  - Tiene dos sintaxis: `#RRGGBBAA` o `RGBA`
  - Los valores para cada cifra va del 1 al 9 y de la A a la F
- _`hsl` | Hue Saturation Lightness_
  - Modelo de color que se define en términos de sus componentes constituyentes
  - Los valores para Hue es del 0 al 360
  - Los valores para Saturation es del 0% al 100%
  - Los valores para Lightness es del 0% al 100%
  - Sintaxis: `hsl(value-hue, value-saturation, value-lightness)`
- _`hsla` | Hue Saturation Lightness Alpha_
  - Funciona igual que hsl pero agrega un cuarto valor el cual define la opacidad del color
  - Los valores para Alpha es de 0 al 1
  - Sintaxis: `hsl(value-hue, value-saturation, value-lightness, value-alpha)`

## _UNIDADES_

- `Unidades Absolutas` | son unidades de medida inalterables, no dependen de ningún factor
  - _`pixeles (px)`_ es la unidad más pequeña de una imagen digital, representando un punto único en una cuadrícula que compone la imagen completa
  - _`centímetros (cm) - pulgadas (in)`_ unidades de medida usadas para impresiones o a cosas aplicadas de forma fisica
- `Unidades Relativas` | son unidades de medida alterables, dependen de algún factor
  - _`porcentajes (%)`_ utilizada para definir valores en relación con un contexto específico, como el tamaño de un contenedor padre
  - _`em`_ es una unidad de medida que representa el tamaño de la fuente del elemento actual. Un valor de "1em" equivale al tamaño de fuente predeterminado del elemento padre.
  - _`rem`_ es una unidad de medida que representa el tamaño de la fuente del elemento raíz del documento (generalmente <html>)
  - _`viewport width (vw)`_ es una unidad de medida que representa el porcentaje del ancho total disponible del viewport del navegador. Se denota con "vw" y permite diseñar de manera más adaptable y sensible a diferentes tamaños de pantalla
  - _`viewport height (vh)`_ es una unidad de medida que representa el porcentaje de la altura total disponible del viewport del navegador. Se denota con "vh" y se utiliza para diseñar de manera adaptable y sensible a diferentes tamaños de pantalla
  - **`viewport max y min (vmax - vmin)`** son unidades de medida en CSS que representan el valor máximo y mínimo entre el ancho y alto del viewport del navegador, respectivamente. Se utilizan para diseñar de manera adaptable y sensible a diferentes tamaños de pantalla, asegurando que los elementos se ajusten correctamente en cualquier dispositivo

## _FONDOS, GRADIENTES Y SOMBRAS_

- `background-color` | propiedad que define el color de fondo de un elemento
- `background-image` | propiedad que permite especificar una imagen como fondo de un elemento
- `background-size` | propiedad que determina el tamaño de una imagen de fondo. Esta propiedad permite ajustar la dimensión de la imagen respecto al elemento que la contiene
- `background-position` | propiedad que especifica la posición inicial de una imagen de fondo dentro del elemento que la contiene. Se usa para controlar dónde se ubicará la imagen respecto con los bordes del elemento
- `background-repeat` | propiedad que determina si una imagen de fondo se repetirá o no en dirección horizontal y/o vertical para cubrir el área del elemento que la contiene
- `background-attachment` | propiedad que determina si una imagen de fondo se desplazará con el contenido de un elemento o permanecerá fija en su posición inicial mientras se desplaza el contenido
- `background` | propiedad que permite definir múltiples aspectos del fondo de un elemento, incluyendo el color, la imagen, posición, repetición y fijación. Es una forma conveniente de especificar varios valores relacionados con el fondo en una sola declaración
- `Gradientes`
  - _`linear-gradient`_ | es una función en CSS que permite crear gradientes lineales, donde los colores se mezclan gradualmente en una dirección específica a lo largo de una línea recta
  - _`radial-gradient`_ | es una función en CSS que permite crear gradientes radiales, donde los colores se mezclan gradualmente desde un punto central hacia afuera en todas las direcciones
  - _`conic-gradient`_ | es una función en CSS que permite crear gradientes cónicos, donde los colores se mezclan circularmente alrededor de un punto central
- `Sombras`
  - _`box-shadow`_ | propiedad que permite agregar sombras a los elementos, creando la ilusión de profundida y elevación
  - _`text-shadow`_ | propiedad que permite agregar sombras al texto de los elementos
  - _`drop-shadow`_ | es una función en CSS que permite aplicar una sombra a un elemento, incluido el contenido y los elementos superpuestos, creando un efecto de sombra proyectada desde el elemento

---
