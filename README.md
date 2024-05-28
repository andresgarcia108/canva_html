# canva_html
# Juego con HTMLS

## Elemento Canvas

- El elemento Canvas, juntos al lenguaje Js nos permite crear animaciones y juegos en el navegador.

- En el navegador el codigo se interpreta de manera secuencial

- Para utilizar el codigo JS, debemos esperar a que todos los elementos HTML hayan sido creados antes de ser utilizados.

- Alternativas:
   - Colocar el script en la parte inferior de la pagina.
   - Utilizar un detector de neventos q nos indique cuando los elementos han sido creados. (Evento onload desde el body o script)

- Se crea una variable canvas por medio del identificador de la etiqueta.
- Se verifica si la variable se  creo correctamente
- En realidad se trabaja con el **contexto** de canvas 2d. Se crea una variable **ctx** con la que se manipula el canvas.
- Se verifica que el contexto se haya creado de manera exitosa dando la bienvenida por medio de un alert()