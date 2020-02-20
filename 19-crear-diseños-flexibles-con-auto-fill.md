# CSS Grid: crear diseños flexibles con auto-fill

La función repeat viene con una opción llamada _auto-fill_. Esto le permite insertar automáticamente tantas filas o columnas del tamaño deseado como sea posible, dependiendo del tamaño del contenedor. Puede crear diseños flexibles al combinar `auto-fill` con `minmax`, de esta manera:

````
repeat(auto-fill, minmax(60px, 1fr));
````

Cuando el contenedor cambia de tamaño, esta configuración sigue insertando columnas de 60px y estirándolas hasta que pueda insertar otra. __Nota:__ Si su contenedor no puede acomodar todos sus artículos en una fila, los moverá a uno nuevo.

----

En el primer grid, use `auto-fill` con `repeat` para llenar el grid con columnas que tengan un ancho mínimo de `60px` y máximo de `1fr`. Luego cambie el tamaño de la vista previa para ver la acción de auto-fill.

La clase `container` debe tener una propiedad gris-template-columns con `repeat` y `auto-fill` que llenará el grid con columnas que tengan un ancho mínimo de `60px` y máximo de `1fr`.

[Desafío #19](https://codepen.io/sebastiantorres86/pen/poJERdG)

----
[Próxima Clase](https://github.com/sebastiantorres86/Curso-CSS-Grid/blob/master/20-crear-dise%C3%B1os-flexibles-con-auto-fit.md)