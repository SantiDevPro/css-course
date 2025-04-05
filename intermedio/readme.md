# 🖌 **CSS INTERMEDIO** 🖌

---

## **Selectores Avanzados**

| Selector              | Descripción                                                            |
| --------------------- | ---------------------------------------------------------------------- |
| `Por atributos`       | seleccionan elementos basados en el valor de sus atributos.            |
| `Descendientes`       | seleccionan elementos hijos anidados dentro de otro elemento.          |
| `Hijos directos`      | seleccionan elementos que son hijos directos de otro elemento.         |
| `Hermanos adyacentes` | seleccionan elementos adyacentes dentro del mismo nivel del árbol DOM. |
| `Hermanos generales`  | seleccionan elementos en el mismo nivel del árbol DOM.                 |

---

## **Herencia, Cascada y Especificidad**

- **Herencia**: los estilos de un elemento padre se aplican a sus hijos, salvo que sean sobrescritos.
- **Cascada**: los estilos se aplican según su origen, especificidad y orden de declaración.
- **Especificidad**: determina qué regla CSS se aplica en caso de conflicto.

---

## **Pseudoclases**

- Palabras clave que especifican un estado especial de un elemento.

### Ejemplos comunes:

| Pseudoclase                    | Descripción                                       |
| ------------------------------ | ------------------------------------------------- |
| `:hover`                       | cuando el cursor pasa sobre el elemento.          |
| `:active`                      | cuando el elemento está activo (clic).            |
| `:focus`                       | cuando el elemento tiene el foco.                 |
| `:visited`                     | para enlaces visitados.                           |
| `:nth-child(n)`                | selecciona el enésimo hijo.                       |
| `:first-child` / `:last-child` | seleccionan el primer/último hijo.                |
| `:is()` / `:where()`           | agrupan selectores.                               |
| `:has()`                       | selecciona elementos que contienen ciertos hijos. |

---

## **Pseudoelementos**

- Permiten aplicar estilos a partes específicas de un elemento.

### Ejemplos comunes:

| Pseudoelemento                    | Descripción                                    |
| --------------------------------- | ---------------------------------------------- |
| `::before` / `::after`            | insertan contenido antes/después del elemento. |
| `::first-line` / `::first-letter` | estilizan la primera línea o carácter.         |
| `::selection`                     | estiliza el texto seleccionado.                |
| `::placeholder`                   | estiliza el texto de marcador de entrada.      |
| `::marker`                        | estiliza los marcadores de lista.              |

---

## **Metodología BEM**

- **BEM**: Block Element Modifier.
- Divide los estilos en bloques, elementos y modificadores para mayor modularidad y mantenibilidad.

---

## **Propiedad Display**

- Controla cómo se muestra un elemento en el diseño.

### Valores comunes:

| Valor           | Descripción                             |
| --------------- | --------------------------------------- |
| `block`         | genera un bloque.                       |
| `inline`        | genera un nivel de línea.               |
| `inline-block`  | nivel de línea con ajuste de tamaño.    |
| `none`          | oculta el elemento.                     |
| `flex` / `grid` | contenedores flexibles o de cuadrícula. |

---

## **Posicionamiento**

### **Relativo y Absoluto**

| Posición   | Descripción                                                          |
| ---------- | -------------------------------------------------------------------- |
| `Relative` | se posiciona en relación con su posición normal.                     |
| `Absolute` | se posiciona en relación con su contenedor principal o el documento. |

### **Fixed y Sticky**

| Posición | Descripción                                                    |
| -------- | -------------------------------------------------------------- |
| `Fixed`  | permanece fijo en la ventana del navegador.                    |
| `Sticky` | mezcla entre relative y fixed, dependiendo del desplazamiento. |

### Propiedades relacionadas:

- `top`, `left`, `right`, `bottom`: controlan la distancia desde los bordes.
- `z-index`: controla el orden de apilamiento.

---

## **Ventanas Modal**

- Interfaz que aparece sobre el contenido principal y requiere interacción antes de continuar.
- Elemento HTML: `<dialog>`.

---

## **Transiciones**

- Efectos de animación para suavizar cambios de propiedades.

### Propiedades clave:

| Propiedad             | Descripción               |
| --------------------- | ------------------------- |
| `transition-property` | propiedades animadas.     |
| `transition-duration` | duración de la animación. |
| `transition-delay`    | tiempo antes de iniciar.  |
| `transition`          | propiedad abreviada.      |

---

## **Desbordamiento (Overflow)**

- Controla cómo manejar el contenido que excede el contenedor.

### Propiedades:

- `overflow`, `overflow-x`, `overflow-y`.

### Valores comunes:

- `visible`, `hidden`, `clip`, `scroll`, `auto`.

---

## **Control de Flujo del Texto**

| Propiedad       | Descripción                                 |
| --------------- | ------------------------------------------- |
| `white-space`   | controla espacios en blanco.                |
| `text-overflow` | maneja texto desbordado (e.g., `ellipsis`). |
| `word-wrap`     | controla cómo se rompen las palabras.       |

---

## **Object Fit y Object Position**

| Propiedad         | Descripción                                           |
| ----------------- | ----------------------------------------------------- |
| `object-fit`      | ajusta cómo `<img>` o `<video>` llenan su contenedor. |
| `object-position` | posiciona el contenido dentro del contenedor.         |

---

## **Contorno (Outline)**

| Propiedad        | Descripción                                                    |
| ---------------- | -------------------------------------------------------------- |
| `outline`        | agrega un contorno sin afectar el diseño.                      |
| `outline-offset` | ajusta la distancia entre el contorno y el borde del elemento. |

---

## **Emmet**

- Herramienta para escribir código HTML y CSS rápidamente mediante atajos.
- Mejora la productividad y legibilidad del código.

---
