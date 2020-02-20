# CSS Grid: use media queries para crear diseños receptivos

CSS Grid puede ser una manera fácil de hacer que su sitio sea más receptivo mediante el uso de media queries para reorganizar las áreas del grid, cambiar las dimensiones de un grid y reorganizar la ubicación de los elementos.

En la vista previa, cuando el ancho de la ventana gráfica es de 300 px o más, el número de columnas cambia de 1 a 2. El área de publicidad ocupa la columna izquierda por completo.

----

Cuando el ancho de la ventana gráfica es de `400px` o más, haga que el área del encabezado ocupe completamente la fila superior y el área del pie de página ocupe la fila inferior por completo.

Cuando la ventana gráfica es de `400px` o más, la clase `container` debe tener una propiedad `grid-template-areas` en la que las áreas de header y footer ocupen las filas superior e inferior, respectivamente, y el advert y el content ocupen las columnas izquierda y derecha de la fila central.

[Desafío #21](https://codepen.io/sebastiantorres86/pen/abOmpKd?editors=1100)

----
[Próxima Clase](#)