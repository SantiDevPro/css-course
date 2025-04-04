# **GRID**

---

## _INTRODUCCION_

- Sistema de diseño que permite crear diseños de página complejos y estructurados mediante la división de la página en filas y columnas

- Permite un posicionamiento preciso de elementos HTML en una cuadrícula bidimensional, lo que facilita la creación de diseños responsivos y flexibles

- `display:"grid"` | propiedad que se utiliza para definir un contenedor como una cuadrícula de elementos

## _CREANDO GRID_

- `grid-cell` | unidad basica donde se puede colocar elementos

- `grid-item` | se refiere a los elementos hijos de un contenedor de cuadrícula o grid

- `grid-lines` | son las líneas de división que definen los bordes de las filas y columnas en una cuadrícula. Pueden ser horizontales (para filas) o verticales (para columnas) y se numeran de manera secuencial

- `grid-tracks` | son las filas o columnas que forman la estructura de la cuadrícula en CSS Grid

- `grid-area` | es una propiedad que especifica en qué área de la cuadrícula debe colocarse un grid-item. Permite asignar un nombre a un área definida en la cuadrícula para su posterior referencia

- `grid-template-columns` | utilizada en un contenedor de cuadrícula para especificar el tamaño, el ancho y el número de columnas de la cuadrícula

- `grid-template-rows` | utilizada en un contenedor de cuadrícula para especificar el tamaño, la altura y el número de filas de la cuadrícula

## _UNIDADES AUTO Y FR_

- `AUTO` | se utiliza para que el tamaño de una fila o columna de la cuadrícula se ajuste automáticamente al contenido de su elemento secundario más grande dentro de esa fila o columna

- `Fr` | se utiliza para distribuir el espacio disponible en una cuadrícula entre las filas o columnas en proporciones definidas. Una fracción (fr) representa una parte igual del espacio disponible después de que se hayan asignado los tamaños explícitos o implícitos a las filas o columnas

## _REPEAT Y MINMAX_

- `repeat()` | se utiliza para especificar la repetición de un número específico de valores

- `minmax()` | se utiliza para definir un rango de tamaños para filas o columnas en una cuadrícula. Toma dos parámetros, el primero especifica el tamaño mínimo y el segundo el tamaño máximo

## _GRID IMPLICITO Y EXPLICITO_

- `Grid Explícito` | se refiere a las filas y columnas definidas explícitamente mediante las propiedades _grid-template-rows_ y _grid-template-columns_. Estas filas y columnas se especifican directamente por el desarrollador

- `Grid Implícito` | se refiere a las filas y columnas generadas automáticamente para acomodar el contenido cuando no se ha especificado un tamaño explícito para una celda en particular. Esto sucede cuando se agregan más elementos de los que se han definido explícitamente en la cuadrícula

- `grid-auto-rows` | propiedad que establece el tamaño por defecto de las filas en un grid implícito. Es decir, definen el tamaño de las filas que se crean automáticamente para acomodar el contenido cuando no se ha especificado un tamaño explícito para una celda en particular

- `grid-auto-columns` | propiedad que establece el tamaño por defecto de las columnas en un grid implícito. Es decir, definen el tamaño de las columnas que se crean automáticamente para acomodar el contenido cuando no se ha especificado un tamaño explícito para una celda en particular

- `grid-auto-flow` | propiedad que determina cómo se colocan automáticamente los elementos en un grid implícito cuando no hay suficiente espacio en las filas o columnas definidas explícitamente. Puede ser _row_, _column_ o _dense_, que controlan si los elementos se distribuyen en filas, columnas o en ambas direcciones, y cómo se reorganizan para llenar los espacios vacíos

## _GRID GAP_

- `column-gap` | propiedad que especifica el espacio entre las columnas

- `row-gap` | propiedad que especifica el espacio entre las filas

- `gap` | propiedad que establece el espacio entre las filas y columnas de una cuadrícula

## _GRID DINAMICO (responsive)_

- `auto-fit` | ajusta automáticamente el número de columnas en la cuadrícula para que quepan en el contenedor sin desbordarse. Las columnas vacías se colapsan

- `auto-fill` | crea tantas columnas como sea posible dentro del contenedor, pero no colapsa las columnas vacías. Si hay más columnas de las que caben en el contenedor, algunas se desbordarán

## _GRID COLUMN Y ROW_

- `grid-column` | propiead abreviada que define el rango de columnas en las que un elemento debe ser colocado dentro de la cuadrícula

- `grid-column-start` | define en qué línea de columna comienza un elemento en una cuadrícula

- `grid-column-end` | define en qué línea de columna termina un elemento en una cuadrícula

- `grid-row` | propiedad abreviada que define el rango de filas en las que un elemento debe ser colocado dentro de la cuadrícula

- `grid-row-start` | define en qué línea de fila comienza un elemento en una cuadrícula

- `grid-row-end` | define en qué línea de fila termina un elemento en una cuadrícula

## _GRID FLOW: Dense_

- `grid-auto-flow: dense` | propiedad que especifica cómo se deben colocar automáticamente los elementos cuando la cuadrícula tiene espacio disponible después de colocar los elementos explícitamente definidos. Cuando se establece en dense, los elementos se llenan en los espacios vacíos de la cuadrícula de manera más compacta, lo que puede resultar en una disposición más eficiente de los elementos

## _GRID AREAS_

- `grid-template-areas` | propiedad que define el diseño de la cuadrícula mediante la asignación de nombres a áreas específicas. Estos nombres se utilizan luego en la propiedad grid-area para colocar elementos en la cuadrícula de acuerdo con el diseño definido

- `grid-area` | propiedad que define el nombre de un área de la cuadrícula y coloca un elemento en esa área. Permite organizar y posicionar elementos en una cuadrícula utilizando nombres de áreas

## _ALINEACION CON GRID_

- `justify-items` | alinea los elementos dentro de sus celdas a lo largo del eje horizontal.

- `align-items` | alinea los elementos dentro de sus celdas a lo largo del eje vertical.

- `justify-content` | alinea el contenido completo de la cuadrícula a lo largo del eje horizontal.

- `align-content` | alinea el contenido completo de la cuadrícula a lo largo del eje vertical.

- `place-items` | propiedad abreviada para combinar `align-items` y `justify-items`.

- `place-content` | propiedad abreviada para combinar `align-content` y `justify-content`.

- `justify-self` | alinea un elemento individual dentro de su celda a lo largo del eje horizontal.

- `align-self` | alinea un elemento individual dentro de su celda a lo largo del eje vertical.

## _SUBGRID_

- Característica que permite que los elementos secundarios de un contenedor de cuadrícula utilicen las líneas de la cuadrícula definidas en el contenedor principal como su propia cuadrícula, lo que facilita la alineación de los elementos secundarios con las líneas de la cuadrícula del contenedor principal

- Esto permite crear diseños más flexibles y complejos alineando las cuadrículas secundarias con las líneas de la cuadrícula principal

---
