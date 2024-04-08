# **ANIMACIONES**

---

## _INTRODUCCION_

- Son una técnica que permite cambiar gradualmente un estilo de un valor a otro durante un período de tiempo

- Se utilizan para crear efectos visuales y de transición en elementos HTML sin necesidad de utilizar JavaScript

- Las animaciones se definen utilizando la regla `@keyframes` y se aplican a los elementos mediante las propiedades `animation` o `transition`

- `animation-name` | especifica el nombre de la animación definida

- `animation-duration` | establece la duración de la animación en segundos o milisegundos

- `animation-delay` | indica el tiempo de espera antes de que la animación comience a ejecutarse

- `animation-fill-mode` | determina cómo se aplicarán los estilos antes y después de la animación. Puede ser none, _forwards_, _backwards_, o _both_

- `animation-timing-function` | determina la velocidad de reproducción de los fotogramas de la animación. Los valores comunes incluyen _ease_, _linear_, _ease-in_, _ease-out_ y _ease-in-out_, entre otros

- `animation-iteration-count` | especifica cuántas veces se repetirá una animación antes de detenerse

- `animation-direction` | determina si una animación debería reproducirse hacia adelante, hacia atrás, alternando entre ambas direcciones o hacia adelante y hacia atrás al final de cada iteración. Toma valores como _normal_, _reverse_, _alternate_, _alternate-reverse_, _initial_ y _inherit_

- `animation-play-state` | determina si una animación está en pausa o en reproducción. Puede tener los valores _running_ para indicar que la animación está en reproducción, y _paused_ para indicar que está en pausa

- `animation` | propiedad combina todas las propiedades de animación en una sola declaración. Permite establecer el nombre, la duración, el retraso, la función de temporización, el número de repeticiones y el estado de la dirección de la animación

## _ANIMACIONES BASADAS EN SCROLL_

- Son efectos dinámicos que se activan según el comportamiento de desplazamiento del usuario en una página web

- Estas animaciones suelen implicar cambios en la apariencia o posición de elementos a medida que el usuario desplaza hacia abajo o hacia arriba en la página

- Se utilizan para crear experiencias de usuario atractivas e interactivas, mejorando el atractivo visual y la interactividad de los sitios web

- `animation-timeline` | es una línea de tiempo que controla la ejecución de una animación

- `scroll-timeline-name` | especifica el nombre de una línea de tiempo de desplazamiento que se usa para controlar las animaciones basadas en el desplazamiento

- `scroll-timeline-axis` | define si la línea de tiempo de desplazamiento se aplica al eje vertical u horizontal

- `scroll-timeline` | forma de controlar la animación mientras el usuario se desplaza por la página. Se puede utilizar para sincronizar animaciones con el desplazamiento del usuario en la ventana del navegador

- `view-timeline` | controla la ejecución de una animación en respuesta a eventos relacionados con la vista, como la carga de una página o la interacción del usuario

- `view-timeline-name` | especifica el nombre de una línea de tiempo de desplazamiento usada para controlar animaciones basadas en el viewport del navegador

- `view-timeline-axis` | define si la línea de tiempo de desplazamiento se aplica al eje vertical u horizontal

## _RANGO DE ANIMACIONES_

- `animation-range` | define un rango de tiempo durante el cual se ejecutará una animación. Permite controlar cuándo comienza y termina una animación en relación con otros eventos en la página

- `animation-range-start` | es el punto de inicio del rango de tiempo definido para una animación. Marca el momento en el que la animación comenzará a reproducirse

- `animation-range-end` | es el punto final del rango de tiempo definido para una animación. Indica cuándo la animación terminará de reproducirse

---
