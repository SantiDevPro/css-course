# 🖌 **CSS AVANZADO** 🖌

---

## **Filtros**

- **`filter`**: Aplica efectos visuales como desenfoque, brillo, saturación, etc., sin alterar el contenido HTML.

  | Efectos         | Descripción                                                        |
  | --------------- | ------------------------------------------------------------------ |
  | `blur()`        | Desenfoque gaussiano.                                              |
  | `brightness()`  | Ajusta el brillo (0% negro, 100% sin cambios).                     |
  | `contrast()`    | Ajusta el contraste (0% gris, 100% sin cambios).                   |
  | `drop-shadow()` | Agrega sombra simulando elevación.                                 |
  | `grayscale()`   | Convierte a escala de grises (0% sin cambios, 100% gris completo). |
  | `hue-rotate()`  | Gira el matiz en un ángulo.                                        |
  | `invert()`      | Invierte colores (0% sin cambios, 100% invertido).                 |
  | `opacity()`     | Ajusta opacidad (0% transparente, 100% opaco).                     |
  | `saturate()`    | Ajusta saturación (0% blanco y negro, 100% sin cambios).           |
  | `sepia()`       | Aplica tono sepia (0% sin cambios, 100% sepia completo).           |

- **`backdrop-filter`**: Aplica efectos al fondo detrás del elemento (ej. desenfoque, cambio de color).

---

## **Transformaciones**

- **`transform`**: Aplica transformaciones 2D/3D como rotaciones, escalados, traslaciones y sesgos.
  - Rotaciones:
    - `rotate()`, `rotateX()`, `rotateY()`, `rotateZ()`.
  - Escalados:
    - `scale()`, `scaleX()`, `scaleY()`, `scaleZ()`.
  - Traslaciones:
    - `translate()`, `translateX()`, `translateY()`, `translateZ()`.
  - Sesgos:
    - `skew()`, `skewX()`, `skewY()`.

---

## **Funciones min(), max() y clamp()**

| Función | Descripción                                                    |
| ------- | -------------------------------------------------------------- |
| `min`   | Retorna el menor de dos valores.                               |
| `max`   | Retorna el mayor de dos valores.                               |
| `clamp` | Limita un valor dentro de un rango (_clamp(min, ideal, max)_). |

---

## **Variables (Custom Properties)**

- Definidas con `--nombre-variable`, reutilizables en todo el CSS.
- Facilitan la gestión de valores como colores, tamaños, etc.

---

## **Función calc()**

- **`calc()`**: Realiza cálculos matemáticos en línea (suma, resta, multiplicación, división) para definir valores dinámicos.

---

## **Propiedades del Scroll**

| Propiedad         | Descripción                                                    |
| ----------------- | -------------------------------------------------------------- |
| `scroll-behavior` | Controla desplazamiento suave o instantáneo.                   |
| `scrollbar-color` | Cambia colores del riel y mango de la barra de desplazamiento. |
| `scrollbar-width` | Ajusta el ancho de la barra de desplazamiento.                 |

---

## **Propiedad initial-letter**

- **`initial-letter`**: Estiliza la primera letra de un elemento (tamaño, estilo, etc.) para efectos decorativos.

---

## **Unidades del Viewport**

- Relativas al tamaño de la ventana gráfica:

  | Unidad                  | Descripción                                                                  |
  | ----------------------- | ---------------------------------------------------------------------------- |
  | `Small Viewport (sv)`   | Dispositivos pequeños (ancho: `svw`, alto: `svh`).                           |
  | `Large Viewport (lv)`   | Dispositivos grandes (ancho: `lvw`, alto: `lvh`).                            |
  | `Dynamic Viewport (dv)` | Considera widgets y diferencias entre pantallas (ancho: `dvw`, alto: `dvh`). |

---

## **Valores min-content, max-content y fit-content**

| Valor         | Descripción                                                    |
| ------------- | -------------------------------------------------------------- |
| `min-content` | Tamaño mínimo necesario sin desbordamiento.                    |
| `max-content` | Tamaño máximo posible sin desbordamiento.                      |
| `fit-content` | Tamaño ajustado entre el mínimo necesario y el máximo posible. |

---

## **Función color-mix()**

- **`color-mix()`**: Mezcla dos colores según un porcentaje.

---

## **Propiedad clip-path**

- **`clip-path`**: Recorta un elemento con formas definidas (círculo, rectángulo, polígono).
- Útil para efectos de recorte personalizados en imágenes o elementos HTML.

---
