# 🖌 **GUÍA DE FLEXBOX** 🖌

---

## 1. Introducción

Flexbox es un modelo de diseño en CSS que facilita la creación de diseños flexibles y responsivos. Permite organizar elementos en una sola dirección (horizontal o vertical) y ajustar su tamaño, alineación y orden dinámicamente.

### Propiedad principal:

- `display: flex`: Activa el contexto de formato flexible en un contenedor.

---

## 2. Propiedades principales

### 2.1 Dirección y envoltura

| Propiedad        | Descripción                                                                                        |
| ---------------- | -------------------------------------------------------------------------------------------------- |
| `flex-direction` | Define la dirección principal de los elementos (_row_, _row-reverse_, _column_, _column-reverse_). |
| `flex-wrap`      | Controla si los elementos se envuelven en múltiples líneas (_nowrap_, _wrap_, _wrap-reverse_).     |
| `flex-flow`      | Combina `flex-direction` y `flex-wrap`.                                                            |

### 2.2 Alineación en los ejes

- **Eje principal (Main Axis)**:
  - `justify-content`: Alinea elementos a lo largo del eje principal.
- **Eje transversal (Cross Axis)**:
  - `align-items`: Alinea elementos a lo largo del eje transversal.
  - `align-content`: Alinea líneas de elementos cuando hay espacio adicional.
- **Espaciado**:
  - `row-gap`: Espacio entre filas.
  - `column-gap`: Espacio entre columnas.
  - `gap`: Combina `row-gap` y `column-gap`.

---

## 3. Orden y tamaño

### 3.1 Orden

- `order`: Cambia el orden de visualización de los elementos sin modificar el DOM.

### 3.2 Tamaño flexible

| Propiedad     | Descripción                                        |
| ------------- | -------------------------------------------------- |
| `flex-basis`  | Tamaño base de un elemento antes de ajustes.       |
| `flex-shrink` | Controla cuánto puede contraerse un elemento.      |
| `flex-grow`   | Controla cuánto puede expandirse un elemento.      |
| `flex`        | Combina `flex-grow`, `flex-shrink` y `flex-basis`. |

---

## 4. Alineación individual

- `align-self`: Ajusta la alineación de un elemento individual en el eje transversal, anulando `align-items` del contenedor.

---

## 5. Diseño con Flexbox

Flexbox permite crear diseños flexibles y responsivos al distribuir dinámicamente el espacio disponible entre los elementos. Es ideal para organizar elementos en una dirección flexible (horizontal o vertical) y controlar su tamaño, alineación y orden de manera eficiente.

---
