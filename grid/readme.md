# 🖌 **GUÍA DE GRID** 🖌

---

## **Introducción**

CSS Grid es un sistema de diseño que permite crear diseños de página complejos y estructurados mediante la división de la página en filas y columnas. Facilita la creación de diseños responsivos y flexibles al permitir un posicionamiento preciso de elementos HTML en una cuadrícula bidimensional.

- **`display: grid`**: Propiedad que define un contenedor como una cuadrícula de elementos.

---

## **Conceptos Básicos**

### **Elementos de la Cuadrícula**

| Propiedad     | Descripción                                                     |
| ------------- | --------------------------------------------------------------- |
| `grid-cell`   | Unidad básica donde se pueden colocar elementos.                |
| `grid-item`   | Elementos hijos de un contenedor de cuadrícula.                 |
| `grid-lines`  | Líneas que definen los bordes de filas y columnas.              |
| `grid-tracks` | Filas o columnas que forman la estructura de la cuadrícula.     |
| `grid-area`   | Define en qué área de la cuadrícula debe colocarse un elemento. |

### **Propiedades Principales**

| Propiedad               | Descripción                                       |
| ----------------------- | ------------------------------------------------- |
| `grid-template-columns` | Especifica el tamaño, ancho y número de columnas. |
| `grid-template-rows`    | Especifica el tamaño, altura y número de filas.   |

---

## **Unidades de Medida**

### **`auto`**

- Ajusta automáticamente el tamaño de una fila o columna al contenido más grande.

### **`fr`**

- Distribuye el espacio disponible en proporciones definidas.

---

## **Funciones Útiles**

### **`repeat()`**

- Especifica la repetición de un número específico de valores.

### **`minmax()`**

- Define un rango de tamaños para filas o columnas (mínimo y máximo).

---

## **Grid Implícito y Explícito**

### **Grid Explícito**

- Filas y columnas definidas explícitamente con `grid-template-rows` y `grid-template-columns`.

### **Grid Implícito**

- Filas y columnas generadas automáticamente para acomodar contenido adicional.

#### Propiedades Relacionadas:

| Propiedad           | Descripción                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------------- |
| `grid-auto-rows`    | Tamaño por defecto de las filas implícitas.                                                 |
| `grid-auto-columns` | Tamaño por defecto de las columnas implícitas.                                              |
| `grid-auto-flow`    | Controla cómo se colocan automáticamente los elementos (valores: `row`, `column`, `dense`). |

---

## **Espaciado en la Cuadrícula**

| Propiedad    | Descripción                     |
| ------------ | ------------------------------- |
| `column-gap` | Espacio entre columnas.         |
| `row-gap`    | Espacio entre filas.            |
| `gap`        | Espacio entre filas y columnas. |

---

## **Grid Dinámico (Responsive)**

| Valor       | Descripción                                                                    |
| ----------- | ------------------------------------------------------------------------------ |
| `auto-fit`  | Ajusta automáticamente el número de columnas para que quepan en el contenedor. |
| `auto-fill` | Crea tantas columnas como sea posible, sin colapsar las columnas vacías.       |

---

## **Posicionamiento en la Cuadrícula**

### **Columnas**

| Propiedad           | Descripción                                   |
| ------------------- | --------------------------------------------- |
| `grid-column`       | Define el rango de columnas para un elemento. |
| `grid-column-start` | Línea donde comienza un elemento.             |
| `grid-column-end`   | Línea donde termina un elemento.              |

### **Filas**

| Propiedad        | Descripción                                |
| ---------------- | ------------------------------------------ |
| `grid-row`       | Define el rango de filas para un elemento. |
| `grid-row-start` | Línea donde comienza un elemento.          |
| `grid-row-end`   | Línea donde termina un elemento.           |

---

## **Flujo de la Cuadrícula**

- **`grid-auto-flow: dense`**: Coloca elementos automáticamente en los espacios vacíos de manera compacta.

---

## **Áreas de la Cuadrícula**

| Propiedad             | Descripción                                                              |
| --------------------- | ------------------------------------------------------------------------ |
| `grid-template-areas` | Define el diseño de la cuadrícula asignando nombres a áreas específicas. |
| `grid-area`           | Coloca un elemento en un área definida.                                  |

---

## **Alineación en la Cuadrícula**

### **Alineación de Elementos**

| Propiedad       | Descripción                                            |
| --------------- | ------------------------------------------------------ |
| `justify-items` | Alinea elementos horizontalmente dentro de sus celdas. |
| `align-items`   | Alinea elementos verticalmente dentro de sus celdas.   |
| `place-items`   | Combina `align-items` y `justify-items`.               |

### **Alineación del Contenido**

| Propiedad         | Descripción                                   |
| ----------------- | --------------------------------------------- |
| `justify-content` | Alinea el contenido completo horizontalmente. |
| `align-content`   | Alinea el contenido completo verticalmente.   |
| `place-content`   | Combina `align-content` y `justify-content`.  |

### **Alineación Individual**

| Propiedad      | Descripción                                    |
| -------------- | ---------------------------------------------- |
| `justify-self` | Alinea un elemento individual horizontalmente. |
| `align-self`   | Alinea un elemento individual verticalmente.   |

---

## **Subgrid**

El subgrid permite que los elementos secundarios utilicen las líneas de la cuadrícula principal como su propia cuadrícula, facilitando la alineación y creando diseños más flexibles y complejos.

---
