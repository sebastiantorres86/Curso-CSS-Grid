# CSS Grid: colocar elementos en áreas de cuadrícula utilizando la propiedad grid-area

Después de crear una plantilla de área para su contenedor grid, como se muestra en el desafío anterior, puede colocar un elemento en su área personalizada haciendo referencia al nombre que le dio. Para hacer esto, use la propiedad grid-area en un elemento como este:

````
.item1 {
   grid-area: header;
}
````

Esto permite que la cuadrícula sepa que desea que la clase `item1` vaya en el área denominada `header`. En este caso, el elemento utilizará toda la fila superior porque esa fila completa se denomina área header.

----

Coloque un elemento con la clase `item5` en el área `footer` utilizando la propiedad `grid-area`.

La clase `item5` debe tener una propiedad `grid-area` que tenga el valor `footer`.

[Desafío #15](https://codepen.io/sebastiantorres86/pen/jOPMyWp)

----
[Próxima Clase](#)