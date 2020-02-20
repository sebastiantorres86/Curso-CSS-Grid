# CSS Grid: limitar el tamaño del elemento con la función minmax

Hay otra función incorporada para usar con `grid-template-columns` y `grid-template-rows` llamada `minmax`. Se utiliza para limitar el tamaño de los elementos cuando el contenedor grid cambia de tamaño. Para hacer esto, debe especificar el rango de tamaño aceptable para su artículo. Aquí hay un ejemplo:

````
grid-template-columns: 100px minmax(50px, 200px);
````

En el código anterior, `grid-template-columns` está configurado para crear dos columnas; el primero tiene un ancho de 100px y el segundo tiene un ancho mínimo de 50px y un ancho máximo de 200px.

----

Usando la función `minmax`, reemplace el `1fr` en la función `repeat` con un tamaño de columna que tenga el ancho mínimo de `90px` y el ancho máximo de `1fr`, y cambie el tamaño del panel de vista previa para ver el efecto.

La clase `container` debe tener una propiedad `grid-template-columns` que esté configurada para repetir 3 columnas con un ancho mínimo de `90px` y un ancho máximo de `1fr`.

[Desafío #18](https://codepen.io/sebastiantorres86/pen/OJVRWjQ)

----
[Próxima Clase](https://github.com/sebastiantorres86/Curso-CSS-Grid/blob/master/19-crear-dise%C3%B1os-flexibles-con-auto-fill.md)