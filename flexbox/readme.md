# **FLEXBOX**

---

## _INTRODUCCION_

- Flexbox es un modelo de diseño en CSS que permite crear diseños más flexibles y eficientes, especialmente para organizar elementos en una sola dirección, ya sea horizontal o verticalmente

- Con Flexbox, los elementos dentro de un contenedor pueden expandirse, contraerse y alinearse automáticamente de manera dinámica, lo que facilita la creación de diseños responsivos y adaptables a diferentes tamaños de pantalla y dispositivo

- `display: flex` | propiedad que se aplica a un contenedor y establece un contexto de formato flexible para los elementos hijos. Con esta propiedad, los elementos hijos dentro del contenedor flex pueden ajustarse automáticamente en tamaño, orden y alineación, lo que facilita la creación de diseños flexibles y responsivos

## _FLEX DIRECTION, FLEX WRAP Y FLEX FLOW_

- `flex-direction` | propiedad que establece la dirección principal en la que se colocan los elementos flex dentro de su contenedor. Puede ser _row_, _row-reverse_, _column_ o _column-reverse_

- `flex-wrap` | propiedad que determina si los elementos flex dentro de su contenedor deben envolverse en múltiples líneas o no. Puede ser _nowrap_, _wrap_ o _wrap-reverse_

- `flex-flow` | propiedad abreviada que combina flex-direction y flex-wrap en una sola declaración. Permite establecer la dirección y el envoltorio de los elementos flex en un solo valor

## _ALINEACION EN LOS EJES_

- `Main Axis` | se refiere a la alineación de los elementos flex a lo largo del eje principal del contenedor flex. Puede ser controlado por las propiedades _justify-content_ y _align-items_

- `Cross Axis` | se refiere a la alineación de los elementos flex a lo largo del eje secundario del contenedor flex. Puede ser controlado por las propiedades _align-items_ y _align-content_

- `justify-content` | controla la alineación de los elementos a lo largo del eje principal del contenedor

- `align-items` | alinea los elementos a lo largo del eje secundario del contenedor

- `align-content` | controla la alineación de las líneas de elementos cuando hay espacio adicional en el eje secundario del contenedor

- `row-gap` | especifica el espacio entre las filas de elementos flexibles en un contenedor flexible en la dirección del bloque, como en una disposición de filas

- `column-gap` | establece el espacio entre las columnas de elementos flexibles en un contenedor flexible en la dirección del bloque, como en una disposición de columnas

- `gap` | propiedad abreviada que establece tanto el espacio entre filas (row-gap) como entre columnas (column-gap) en un solo valor

## _ORDER_

- `order` | permite especificar el orden de visualización de elementos flexibles dentro de su contenedor, sin alterar la estructura del DOM. Se asigna un valor numérico para determinar el orden de aparición, donde los elementos con valores más bajos se muestran primero

## _FLEX BASIS, SHRINK Y GROW_

- `flex-basis` | define el tamaño base de un elemento flexible antes de que se distribuya el espacio adicional o se ajuste según las reglas de flexibilidad

- `flex-shrink` | determina cómo un elemento flexible debe contraerse si es necesario para ajustarse dentro de un contenedor flexible en función del espacio disponible

- `flex-grow` | especifica cuánto espacio adicional puede ocupar un elemento flexible dentro de un contenedor flexible en función del espacio disponible

- `flex` | propiedad que combina tres propiedades individuales: flex-grow, flex-shrink y flex-basis. Esta propiedad determina la capacidad de un elemento flexible para crecer, contraerse y su tamaño base en un contenedor flexible

## _ALIGN SELF_

- `align-self` | propiedad que controla la alineación de un elemento flexible a lo largo del eje transversal del contenedor flexible. Permite ajustar la alineación vertical de un elemento individualmente dentro de un contenedor flexible, anulando la alineación definida por la propiedad align-items del contenedor padre

## _LAYOUT CON FLEXBOX_

- Es una técnica de diseño que utiliza el modelo de caja flexible para organizar los elementos de una página web en una dirección flexible, ya sea horizontal o vertical

- Permite crear diseños flexibles y responsivos mediante la distribución dinámica del espacio disponible entre los elementos, controlando su tamaño, alineación y ordenamiento de manera eficiente

---
