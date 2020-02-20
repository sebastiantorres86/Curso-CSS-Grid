# CSS Grid: divide la cuadrícula en una plantilla de área

Puede agrupar celdas de su grid en un _área_ y asignarle un nombre personalizado. Haga esto usando `grid-template-areas` en el contenedor de esta manera:

````
grid-template-areas:
   "header header header"
   "advert content content"
   "footer footer footer";
````

El código anterior combina las tres celdas superiores en un área denominada `header`, las tres celdas inferiores en un área de `footer`, y forma dos áreas en la fila central; `advert` y `content`. __Nota__: Cada palabra en el código representa una celda y cada par de comillas representa una fila. Además de las etiquetas personalizadas, puede usar un punto (`.`) Para designar una celda vacía en la cuadrícula.

----
Coloque la plantilla de área de modo que la celda etiquetada como `advert` se convierta en una celda vacía.

La clase `container` debe tener una propiedad `grid-template-areas` similar a la vista previa pero tiene un `.` en lugar del área `advert`.

[Desafío #14](https://codepen.io/sebastiantorres86/pen/LYVRxpV)

----
[Próxima Clase](#)