# **RESPONSIVE DESIGN**

---

## _BLOQUES Y MULTIMEDIA FLEXIBLE_

- `min-width` | especifica la anchura mínima que puede tener un elemento antes de que se le permita reducirse más en tamaño

- `max-width` | define la anchura máxima que puede alcanzar un elemento antes de que comience a reducirse en tamaño

- `min-height` | establece la altura mínima que puede tener un elemento antes de que se le permita encogerse más en altura

- `max-height` | determina la altura máxima que puede alcanzar un elemento antes de comenzar a encogerse en altura

## _SRCSET Y SIZES_

- `srcset` | atributo de las etiquetas _`<img>`_ y _`<source>`_ que permite especificar una serie de imágenes y sus correspondientes tamaños y densidades de píxeles. Esto ayuda al navegador a seleccionar automáticamente la imagen más adecuada según las características de la pantalla del usuario, como la densidad de píxeles

- `sizes` | atributo de la etiqueta _`<img>`_ que se utiliza junto con el atributo _srcset_ para indicar al navegador qué tamaño de imagen debe usar en función del ancho del contenedor de la imagen. Se especifica utilizando una lista de pares de valores ancho-tamaño, donde el tamaño representa la distancia horizontal disponible para la imagen

## _PICTURE, SOURCE Y MEDIA_

- `picture` | se utiliza para contener una o más etiquetas _`<source>`_ y una etiqueta _`<img>`_ para proporcionar una forma flexible y compatible con la capacidad de respuesta para mostrar imágenes en una página web

- `source` | se utiliza dentro de un elemento _`<picture>`_ para especificar varias fuentes de imagen para el navegador, cada una con su propio atributo _srcset_ que contiene la ruta de la imagen y su densidad de píxeles correspondiente

- `media` | atributo utilizado en el elemento _`<source>`_ que especifica el atributo de medios al cual se aplica la fuente de la imagen definida en el _srcset_. Permite condicionar la carga de la imagen en función de las características del dispositivo, como el tamaño de la pantalla o la resolución

## _MEDIA QUERIES_

- Son reglas que permiten aplicar estilos específicos basados en características del dispositivo, como el ancho de la pantalla, la orientación, la resolución, etc

- Esto facilita la creación de sitios web adaptables a diferentes dispositivos y tamaños de pantalla

- Las media queries se utilizan para crear diseños responsivos y mejorar la experiencia del usuario en diferentes dispositivos

## _MOBILE FIRST_

- Es una estrategia de diseño web que prioriza el diseño y desarrollo de un sitio web para dispositivos móviles antes que para dispositivos de escritorio

- Esto implica comenzar el diseño desde una perspectiva móvil y luego ir progresando hacia tamaños de pantalla más grandes

- La filosofía detrás de mobile first es asegurar que el sitio web sea óptimo y funcional en dispositivos móviles, que suelen tener limitaciones de ancho de banda y recursos de hardware, antes de adaptarlo a dispositivos más grandes

- Esto promueve un enfoque centrado en el usuario y mejora la accesibilidad y la usabilidad del sitio en general

## _FEATURE QUERIES_

- Son una técnica que permite aplicar estilos basados en la presencia o ausencia de ciertas características en el navegador o dispositivo del usuario

- Esto permite adaptar el diseño y la apariencia del sitio web según las capacidades del navegador, como soporte para ciertas propiedades CSS, características de JavaScript, resolución de pantalla, tamaño de la ventana del navegador, entre otros

- Las feature queries se realizan utilizando la regla `@supports` en CSS, que evalúa si el navegador es compatible con una determinada característica o propiedad antes de aplicar estilos específicos

- Esto ayuda a garantizar que los estilos se apliquen de manera coherente en una amplia variedad de dispositivos y navegadores

## _CONTAINER QUERIES_

- Son una técnica que permite aplicar estilos basados en el tamaño y características de un contenedor HTML, en lugar de las características del navegador o dispositivo del usuario

- Esto significa que los estilos pueden cambiar dinámicamente según el tamaño del contenedor que los rodea, lo que facilita la creación de diseños más flexibles y adaptables

- Las container queries están diseñadas para funcionar de manera similar a las media queries, pero en lugar de responder a las características del dispositivo, responden al tamaño y contexto del contenedor padre

- Esto permite crear componentes web más modulares y reutilizables, ya que los estilos pueden ajustarse automáticamente según el espacio disponible en el contenedor que los contiene

---
