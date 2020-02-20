# CSS Grid: crear diseños flexibles con auto-fit

`auto-fit` funciona casi de manera idéntica a `auto-fill`. La única diferencia es que cuando el tamaño del contenedor excede el tamaño de todos los elementos combinados, el `auto-fill` sigue insertando filas o columnas vacías y empuja sus elementos hacia un lado, mientras que `auto-fit` contrae esas filas o columnas vacías y estira sus elementos para adaptarse al tamaño del contenedor.

__Nota:__ Si su contenedor no puede acomodar todos sus artículos en una fila, los moverá a uno nuevo.

----
En el segundo grid, use `auto-fit` con `repeat` para llenar el grid con columnas que tengan un ancho mínimo de `60px` y máximo de `1fr`. Luego, cambie el tamaño de la vista previa para ver la diferencia.

La clase `container2` debe tener una propiedad `grid-template-columns` con `repeat` y `auto-fit` que llene el grid con columnas que tengan un ancho mínimo de `60px` y un máximo de `1fr`.

[Desafío #20](https://codepen.io/sebastiantorres86/pen/OJVRWQvG)

----
[Próxima Clase](#)