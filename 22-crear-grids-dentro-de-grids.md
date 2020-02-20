# CSS Grid: crear grids dentro de grids

Convertir un elemento en un grid solo afecta el comportamiento de sus descendientes directos. Entonces, al convertir un descendiente directo en un grid, tiene un grid dentro de un grid.

Por ejemplo, al establecer las propiedades `display` y `grid-template-columns` del elemento con la clase `item3`, crea un grid dentro de su grid.

----

Convierta el elemento con la clase `item3` en un grid con dos columnas con un ancho de `auto `y `1fr` usando `display` y `grid-template-columns`.

La clase `item3` debe tener una propiedad `grid-template-columns` con `auto` y `1fr` como valores.
La clase `item3` debe tener una propiedad `display` con el valor de `grid`.

[Desafío #22](https://codepen.io/sebastiantorres86/pen/JjdREaR)

----