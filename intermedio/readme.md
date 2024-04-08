# **CSS INTERMEDIO**

---

## _SELECTORES (avanzado)_

- `Selectores por atributos` | seleccionan elementos basados en el valor de sus atributos

- `Selectores descendientes` | seleccionan elementos hijos que están anidados dentro de otro elemento, independientemente de su nivel de profundidad

- `Selectores de hijos directos` | seleccionan elementos que son hijos directos de otro elemento, sin importar cuántos niveles de profundidad haya entre ellos

- `Selectores de hermanos adyacentes` | seleccionan elementos que son adyacentes a otro elemento dentro del mismo nivel del árbol DOM

- `Selectores de hermanos generales` | seleccionan elementos basados en la presencia de otros elementos en el mismo nivel del árbol DOM

## _HERENCIA, CASCADA Y ESPECIFICIDAD_

- `Herencia` | es el proceso por el cual un elemento hijo hereda los estilos definidos en su elemento padre. Los estilos de un elemento padre pueden aplicarse a sus elementos hijos a menos que sean anulados o sobrescritos por estilos más específicos

- `Cascada (cascading)` | se refiere al proceso mediante el cual se aplican y combinan los estilos CSS en un documento. Los estilos se aplican en función de su origen (como el autor, el usuario o el agente de usuario), su especificidad y su orden de declaración

- `Especificidad` | es un concepto que determina qué regla CSS se aplica cuando hay conflictos entre diferentes estilos que se aplican a un mismo elemento. La especificidad se basa en el tipo de selector, el número de selectores y los selectores de mayor peso tienen prioridad sobre los de menor peso

## _PSEUDOCLASES_

- Son palabras clave que se agregan a los selectores CSS y que especifican un estado especial del elemento seleccionado

- Algunas pseudoclases más usados:

  - `:hover` | se aplica cuando el usuario pasa el cursor sobre el elemento

  - `:active` | se aplica cuando el elemento está activo, como cuando se hace clic en él

  - `:focus` | se aplica cuando el elemento tiene el foco del usuario

  - `:visited` | se aplica a un enlace que ha sido visitado por el usuario

  - `:nth-child()` | selecciona elementos que son el enésimo hijo de su padre

  - `:first-child` | selecciona el primer hijo de su padre

  - `:last-child` | selecciona el último hijo de su padre

  - `:nth-of-type()` | selecciona elementos basados en su posición entre los elementos de un tipo específico

  - `first-of-type` | selecciona el primer elemento de su tipo dentro de su padre

  - `last-of-type` | selecciona el último elemento de su tipo dentro de su padre

  - `:is()` | permite agrupar selectores CSS en una lista y aplicar un conjunto de estilos a los elementos que coincidan con cualquiera de los selectores de la lista

  - `:where()` | agrupa un conjunto de selectores, pero no afecta la especificidad de los selectores contenidos. Esto significa que los selectores dentro de :where() no afectarán la especificidad del selector general

  - `:has()` | selecciona elementos que contienen ciertos elementos secundarios específicos

## _PSEUDOELEMENTOS_

- Son elementos virtuales que se agregan a ciertos selectores CSS y que permiten aplicar estilos a partes específicas de un elemento

- Algunos pseudoelementos más usados:

  - `::before` | permite insertar contenido antes del contenido de un elemento

  - `::after` | permite insertar contenido después del contenido de un elemento

  - `::first-line` | permite aplicar estilos específicos a la primera línea de texto dentro de un elemento

  - `::first-letter` | permite aplicar estilos específicos al primer carácter de texto dentro de un elemento

  - `::selection` | permite aplicar estilos al texto seleccionado por el usuario

  - `::placeholder` | permite estilizar el texto de marcador de posición en los campos de entrada _`input`_ y área de texto _`textarea`_

  - `::marker` | permite estilizar los marcadores de lista (list-item) de una lista ordenada o no ordenada

  - `::backdrop` | permite aplicar estilos al fondo detrás de un cuadro de diálogo modal cuando está visible

## _METODOLOGIA BEM_

- `BEM` | Block Element Modifier

- Es un enfoque de nomenclatura para escribir clases en CSS de manera más modular y mantenible

- Es una metodología de nomenclatura que divide los estilos de CSS en bloques, elementos y modificadores, lo que facilita la creación de estilos reutilizables y predecibles para componentes de interfaz de usuario

## _DISPLAY_

- Atributo que controla cómo se muestra un elemento en el diseño de la página

- Define el tipo de caja que un elemento genera y, por lo tanto, cómo se colocan y estructuran los elementos en el flujo del documento

- Algunos valores para display son:

  - `block` | elemento genera un bloque de nivel de bloque

  - `inline` | elemento genera un nivel de línea

  - `inline-block` | elemento genera un nivel de línea, pero permite ajustar el ancho y la altura

  - `none` | elemento no se muestra en absoluto

  - `inherit` | elemento hereda el valor de display de su elemento padre

  - `flex` | elemento se convierte en un contenedor flexible

  - `grid` | elemento se convierte en un contenedor de cuadrícula

## _POSICION RELATIVA Y ABSOLUTA_

- `Position Absolute` | coloca un elemento en relación con su contenedor principal o, si no hay uno, con el cuerpo del documento. El elemento se elimina del flujo normal del documento, lo que significa que no afecta el posicionamiento de otros elementos. Se puede desplazar utilizando las propiedades top, right, bottom y left

- `Position Relative` | coloca un elemento en relación con su posición normal en el flujo del documento. El elemento conserva su espacio en el diseño normal del documento y luego se puede desplazar utilizando las propiedades top, right, bottom y left, pero su desplazamiento no afecta a otros elementos

- `top` | propiedad que especifica la distancia entre el borde superior del elemento y el borde superior del elemento primario más cercano posicionado

- `left` | propiedad que especifica la distancia entre el borde izquierdo del elemento y el borde izquierdo del elemento primario más cercano posicionado

- `right` | propiedad que especifica la distancia entre el borde derecho del elemento y el borde derecho del elemento primario más cercano posicionado

- `bottom` | propiedad que especifica la distancia entre el borde inferior del elemento y el borde inferior del elemento primario más cercano posicionado

- `z-index` | propiedad que controla el orden de apilamiento de los elementos posicionados en el eje Z (profundidad) del plano de visualización

## _VENTANAS MODAL_

- Es una interfaz de usuario que aparece encima del contenido principal de una página web y requiere que el usuario interactúe con ella antes de poder volver a acceder al contenido subyacente

- Por lo general, se utiliza para mostrar información importante, solicitar confirmación de acciones o recopilar datos adicionales del usuario

- Las ventanas modales suelen destacarse visualmente del resto de la página y pueden cerrarse haciendo clic fuera de ellas o en un botón específico de cierre

- `dialog` | elemento HTML que representa una ventana de diálogo modal en una página web. Se utiliza para mostrar información importante, solicitar confirmación de acciones o recopilar datos adicionales del usuario. A diferencia de otras ventanas modales, un diálogo no se bloquea, lo que significa que el usuario puede interactuar con el resto de la página mientras está abierto. Sin embargo, la atención del usuario está centrada en el diálogo hasta que se cierre o se resuelva

## _POSICION FIXED Y STICKY_

- `Position Fixed` | este valor de posición hace que un elemento se fije en una posición específica en relación con la ventana del navegador, lo que significa que permanecerá en esa posición incluso cuando se desplaza la página

- `Position Sticky` | este valor de posición es una mezcla entre relative y fixed. Un elemento con position sticky se comportará como relative hasta que se desplace a una posición determinada, momento en el que se volverá fixed, permaneciendo fijo en esa posición mientras el contenedor es visible en la ventana del navegador

## _TRANSICIONES_

- Son efectos de animación que se aplican a propiedades específicas, como color, tamaño, posición, etc., cuando cambian de un estado a otro

- Permiten suavizar el cambio entre los valores de las propiedades a lo largo del tiempo, creando efectos visuales más agradables y atractivos en las interfaces web

- `transition-property` | especifica qué propiedades deben ser animadas durante la transición

- `transition-duration` | define la duración de la transición, es decir, cuánto tiempo debe tomar para que se complete la animación

- `transition-delay` | indica el tiempo de espera antes de que comience la transición

- `transition` | propiedad abreviada que permite establecer de manera conjunta todas las propiedades de transición (property, duration, timing function y delay) en una sola declaración

## _DESBORDAMIENTO (overflow)_

- `overflow-x` | se utiliza para controlar el desbordamiento horizontal

- `overflow-y` | se utiliza para controlar el desbordamiento vertical

- `overflow` | propiedad que controla cómo se comporta el contenido que desborda el contenedor en el que está contenido. Permite establecer overflow-x y overflow-y simultáneamente en un solo lugar

- Todas estas propiedades pueden tener los valores: _`visible`_, _`hidden`_, _`clip`_, _`scrool`_ y _`auto`_, que determinan cómo manejar el desbordamiento en esa dirección específica

## _CONTROL DE FLUJO DEL TEXTO_

- `white-space` | propiedad que controla cómo se manejan los espacios en blanco dentro del elemento. Puede tener valores como _normal_, _nowrap_, _pre_, _pre-wrap_ y _pre-line_.

- `text-overflow` | propiedad que controla cómo se maneja el texto que desborda su contenedor en la dirección horizontal. Puede tener valores como _clip_ o _ellipsis_.

- `text-wrap` | controla cómo se deben romper las palabras cuando no caben en una línea dentro de un contenedor. En normal, las palabras largas pueden desbordar su contenedor. Si se establece en break-word, las palabras largas pueden dividirse en varias líneas para ajustarse al contenedor

- `word-wrap` | controla cómo se rompen las palabras cuando no caben en una línea. Puede tener valores como _normal_ o _break-word_.

## _OBJECT FIT Y OBJECT POSITION_

- `Object Fit` | controla cómo se ajusta un elemento `<img>` o `<video>` dentro de su contenedor. Puede especificar cómo el contenido debe escalarse para llenar el contenedor utilizando valores como _fill_, _contain_, _cover_, _none_, _scale-down_

- `Object Position` | determina la posición del contenido dentro del contenedor en relación con los ejes X e Y

## _CONTORNO (outline)_

- `outline` | se utiliza para agregar un contorno alrededor de un elemento, pero sin afectar el diseño del flujo del documento ni el tamaño total del elemento

- `outline-offset` | ajusta la distancia entre el borde del contorno (outline) y el borde del elemento. Esto permite controlar el espacio entre el contorno y el borde del elemento

## _EMMET_

- Emmet es un conjunto de abreviaturas y atajos de teclado utilizados principalmente en editores de código para agilizar y simplificar la escritura de código HTML y CSS

- Con Emmet, los desarrolladores pueden escribir de manera rápida y eficiente código HTML y CSS utilizando atajos de teclado que se expanden automáticamente en código completo

- Esto aumenta la productividad al reducir la cantidad de tiempo necesario para escribir código repetitivo y mejorar la legibilidad del código

---
