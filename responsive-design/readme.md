# 🖌 **RESPONSIVE DESIGN** 🖌

El diseño responsivo es una técnica de diseño web que permite que los sitios web se adapten a diferentes tamaños de pantalla y dispositivos, mejorando la experiencia del usuario. A continuación, se describen los conceptos clave y herramientas utilizadas en el diseño responsivo.

---

## **1. BLOQUES Y MULTIMEDIA FLEXIBLE**

| Propiedad    | Descripción                                                 |
| ------------ | ----------------------------------------------------------- |
| `min-width`  | Define la anchura mínima que puede tener un elemento.       |
| `max-width`  | Establece la anchura máxima que puede alcanzar un elemento. |
| `min-height` | Especifica la altura mínima que puede tener un elemento.    |
| `max-height` | Determina la altura máxima que puede alcanzar un elemento.  |

---

## **2. IMÁGENES RESPONSIVAS**

### **2.1. Atributos `srcset` y `sizes`**

- **`srcset`**: Permite especificar una serie de imágenes con diferentes tamaños y densidades de píxeles. El navegador selecciona automáticamente la más adecuada.
- **`sizes`**: Indica al navegador qué tamaño de imagen usar según el ancho del contenedor.

### **2.2. Elementos `picture` y `source`**

- **`<picture>`**: Contiene etiquetas `<source>` y `<img>` para mostrar imágenes adaptables.
- **`<source>`**: Define varias fuentes de imagen con el atributo `srcset`.
- **`media`**: Atributo en `<source>` que condiciona la carga de imágenes según características del dispositivo (tamaño de pantalla, resolución, etc.).

---

## **3. MEDIA QUERIES**

- Permiten aplicar estilos específicos según características del dispositivo (ancho de pantalla, orientación, resolución, etc.).
- Facilitan la creación de sitios web adaptables y mejoran la experiencia del usuario.

---

## **4. MOBILE FIRST**

- Estrategia que prioriza el diseño para dispositivos móviles antes que para escritorio.
- Beneficios:
  - Optimización para dispositivos con limitaciones de ancho de banda y hardware.
  - Mejora la accesibilidad y usabilidad del sitio.

---

## **5. FEATURE QUERIES**

- Permiten aplicar estilos según la compatibilidad del navegador con ciertas características.
- Se utilizan con la regla `@supports` en CSS:
  ```css
  @supports (display: grid) {
    /* Estilos específicos */
  }
  ```
- Garantizan consistencia en una amplia variedad de dispositivos y navegadores.

---

## **6. CONTAINER QUERIES**

- Aplican estilos basados en el tamaño y características de un contenedor HTML, en lugar del dispositivo.
- Ventajas:
  - Diseños más flexibles y adaptables.
  - Componentes web más modulares y reutilizables.
- Funcionan de manera similar a las media queries, pero responden al tamaño del contenedor padre.

---
