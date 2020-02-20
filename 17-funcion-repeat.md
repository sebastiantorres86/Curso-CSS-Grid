# CSS Grid: reducir la repetición utilizando la función repeat

Cuando utilizó `grid-template-columns` y `grid-template-rows` para definir la estructura de un grid, ingresó un valor para cada fila o columna que creó.

Digamos que desea un grid con 100 filas de la misma altura. No es muy práctico insertar 100 valores individualmente. Afortunadamente, hay una mejor manera: mediante el uso de la función `repeat` para especificar la cantidad de veces que desea que se repita su columna o fila, seguido de una coma y el valor que desea repetir.

Aquí hay un ejemplo que crearía la cuadrícula de 100 filas, cada fila de 50px de alto.

````
grid-template-rows: repeat(100, 50px);
````
También puede repetir múltiples valores con la función de repetición e insertar la función entre otros valores al definir una estructura grid. Así es como se ve:

````
grid-template-columns: repeat(2, 1fr 50px) 20px;
`````

Esto se traduce en:

````
grid-template-columns: 1fr 50px 1fr 50px 20px;
````

__Nota:__ El `1fr 50px` se repite dos veces seguido de 20px.

----

Use `repeat` para eliminar la repetición de la propiedad `grid-template-columns`.

La clase `container` debería tener una propiedad `grid-template-columns` que esté configurada para repetir 3 columnas con el ancho de `1fr`.

[Desafío #17](https://codepen.io/sebastiantorres86/pen/abOmpWz)

----
[Próxima Clase](https://github.com/sebastiantorres86/Curso-CSS-Grid/blob/master/18-limitar-tama%C3%B1o-elemento-con-minmax.md)