# CSS Grid: Use grid-column para controlar el espaciado

Hasta este punto, todas las propiedades que se han discutido son para contenedores grid. La propiedad grid-column es la primera que se usa en los elementos del grid.

Las líneas horizontales y verticales hipotéticas que crean el grid se denominan _líneas_. Estas líneas están numeradas comenzando con 1 en la esquina superior izquierda de la cuadrícula y se mueven hacia la derecha para columnas y hacia abajo para filas, contando hacia arriba.

Para controlar la cantidad de columnas que consumirá un elemento, puede usar la propiedad `grid-column` junto con los números de línea en los que desea que el elemento comience y se detenga.

Aquí hay un ejemplo:
````
grid-column: 1/3;
````

Esto hará que el elemento comience en la primera línea vertical de la cuadrícula a la izquierda y se extienda hasta la tercera línea de la cuadrícula, consumiendo dos columnas.

----
Haga que el elemento con la clase `item5` consuma las dos últimas columnas del grid.

La clase `item5` debería tener una propiedad `grid-column`.
La clase `item5` debe tener una propiedad `grid-column` que haga que consuma las dos últimas columnas del grid.

[Desafío #8](https://codepen.io/sebastiantorres86/pen/zYGKowL)

----
[Próxima Clase](#)