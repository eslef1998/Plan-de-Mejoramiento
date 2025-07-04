# Proyecto: Interfaz tipo Bento Grid

## Cómo estructuré el layout

Usé HTML y CSS para hacer una página con varias secciones organizadas en una cuadrícula. 
Para pantallas grandes (como computadores), usé CSS Grid con 10 columnas y 10 filas.
Cada sección tiene su propia clase (como `.box-one`, `.box-two`, etc.) para poder darle estilos y ubicarla en el lugar correcto.

Para que la página se vea bien en tablets y celulares, usé media queries. 
n tablets (pantallas medianas) cambié el diseño a dos columnas, y en celulares (pantallas pequeñas)
todo se muestra en una sola columna, una sección debajo de la otra.

## Qué retos enfrenté

Uno de los problemas fue que algunas secciones se desordenaban cuando la pantalla era más pequeña.
Tuve que ajustar los tamaños de texto, imágenes y quitar transformaciones como `translate`
que hacían que los elementos se salieran del lugar.

También me costó un poco entender cómo hacer que el diseño se adaptara bien en tablets, 
porque no es tan grande como una computadora pero tampoco tan pequeño como un celular.

## Qué aprendí del ejercicio

Aprendí a usar mejor CSS Grid y cómo combinarlo con media queries para que el diseño funcione en diferentes tamaños de pantalla.
También entendí que es importante probar el diseño en varios dispositivos y resoluciones para que no se rompa.

Además, practiqué cómo organizar mejor mi código CSS y cómo comentar solo lo necesario para que sea más fácil de leer.

