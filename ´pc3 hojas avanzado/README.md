# Portafolio Interactivo - HRG Construmet

Practica Calificada 3 del curso de CSS Avanzado. Hice una landing page para HRG Construmet, una empresa metalmecanica que trabaja para la mineria. Use HTML, CSS y Bootstrap 5.

## Transformaciones

- En la seccion Proyectos hay 3 cajas que cambian al pasar el mouse: la primera rota (rotate), la segunda se agranda (scale) y la tercera sube y se inclina (translate y skew). Les puse transition para que no se vea brusco.
- La tarjeta de Mision es la parte 3D. El contenedor tiene perspective y la tarjeta tiene transform-style: preserve-3d, y al pasar el mouse gira con rotateX y rotateY para mostrar la parte de atras.

## Animaciones

- Al abrir la pagina sale un loader (un circulo girando) que se va solo a los 2 segundos.
- El titulo y el texto del inicio entran deslizandose desde la izquierda.
- El circulo con las letras HRG cambia de color y tamaño todo el tiempo.

Para controlarlas use animation-duration, animation-iteration-count, animation-timing-function y animation-direction.

Tambien agregue el prefijo -webkit- en algunas propiedades para que funcione mejor en Safari.
