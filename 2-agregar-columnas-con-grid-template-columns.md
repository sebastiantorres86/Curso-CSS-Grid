# CSS Grid: agregar columnas con grid-template-columns

Simplemente crear un elemento grid no te lleva muy lejos. También debe definir la estructura del grid. Para agregar algunas columnas al grid, use la propiedad `grid-template-columns` en un contenedor grid como se muestra a continuación:
````
.container {
   display: grid;
   gird-template-columns: 50px 50px;
}
````

Esto le dará a grid dos columnas de 50px de ancho cada una. El número de parámetros dados a la propiedad `grid-template-columns` indica el número de columnas en la cuadrícula, y el valor de cada parámetro indica el ancho de cada columna.

----
Dele al contenedor grid tres columnas de `100px` de ancho cada una.

[Desafío #2](https://codepen.io/sebastiantorres86/pen/RwPGGqd?editors=1100)

La clase `container` debería tener una propiedad `grid-template-columns` con tres unidades de `100px`.

----
[Próxima Clase](https://github.com/sebastiantorres86/Curso-CSS-Grid/blob/master/3-agregar-filas-con-grid-template-rows.md)
