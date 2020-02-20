# CSS Grid: use unidades de grid CSS para cambiar el tamaño de columnas y filas

Puede usar unidades absolutas y relativas como `px` y `em` en CSS Grid para definir el tamaño de las filas y columnas. También puedes usar estos:

`fr`: establece la columna o fila en una fracción del espacio disponible,

`auto`: establece la columna o fila al ancho o alto de su contenido automáticamente,

`%`: ajusta la columna o fila al ancho porcentual de su contenedor.

Aquí está el código que genera la salida en la vista previa:

````
grid-template-columns: auto 50px 10% 2fr 1fr;
````

Este snippet crea cinco columnas. La primera columna es tan ancha como su contenido, la segunda columna es de 50 px, la tercera columna es el 10% de su contenedor, y para las dos últimas columnas; el espacio restante se divide en tres secciones, dos se asignan para la cuarta columna y una para la quinta.

----
Haga un grid con tres columnas cuyos anchos sean los siguientes: 1fr, 100px y 2fr.

La clase `container` debe tener una propiedad `grid-template-columns` que tenga tres columnas con los siguientes anchos: `1fr, 100px y 2fr`.

[Desafío #4](https://codepen.io/sebastiantorres86/pen/xxGEEoz)

----
[Próxima Clase](#)