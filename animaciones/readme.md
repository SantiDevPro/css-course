# 🖌 **GUÍA DE ANIMACIONES** 🖌

---

## **Introducción**

Las animaciones en CSS permiten cambiar gradualmente un estilo de un valor a otro durante un período de tiempo. Se utilizan para crear efectos visuales y transiciones en elementos HTML sin necesidad de JavaScript.

### **Propiedades principales de animaciones**

- **`@keyframes`**: Define los fotogramas de una animación.
- **`animation`**: Combina todas las propiedades de animación en una sola declaración.

### **Propiedades individuales**

| Propiedad                   | Descripción                                                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------ |
| `animation-name`            | Nombre de la animación definida.                                                                       |
| `animation-duration`        | Duración de la animación (en segundos o milisegundos).                                                 |
| `animation-delay`           | Tiempo de espera antes de que la animación comience.                                                   |
| `animation-fill-mode`       | Cómo se aplican los estilos antes y después de la animación (`none`, `forwards`, `backwards`, `both`). |
| `animation-timing-function` | Velocidad de reproducción de los fotogramas (`ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`).  |
| `animation-iteration-count` | Número de repeticiones de la animación.                                                                |
| `animation-direction`       | Dirección de la animación (`normal`, `reverse`, `alternate`, `alternate-reverse`).                     |
| `animation-play-state`      | Estado de la animación (`running`, `paused`).                                                          |

---

## **Animaciones basadas en scroll**

Estas animaciones se activan según el desplazamiento del usuario en la página, creando experiencias interactivas y atractivas.

### **Propiedades principales**

- **`animation-timeline`**: Controla la ejecución de una animación.
- **`scroll-timeline`**: Sincroniza animaciones con el desplazamiento del usuario.
  - **`scroll-timeline-name`**: Nombre de la línea de tiempo de desplazamiento.
  - **`scroll-timeline-axis`**: Eje de aplicación (`vertical`, `horizontal`).
- **`view-timeline`**: Controla animaciones basadas en eventos relacionados con la vista.
  - **`view-timeline-name`**: Nombre de la línea de tiempo de vista.
  - **`view-timeline-axis`**: Eje de aplicación (`vertical`, `horizontal`).

---

## **Rango de animaciones**

Permite definir un rango de tiempo para controlar cuándo comienza y termina una animación.

| Propiedad               | Descripción                                   |
| ----------------------- | --------------------------------------------- |
| `animation-range`       | Rango de tiempo de ejecución de la animación. |
| `animation-range-start` | Punto de inicio del rango.                    |
| `animation-range-end`   | Punto final del rango.                        |

---
