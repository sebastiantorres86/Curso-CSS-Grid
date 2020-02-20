# CSS Grid: use grid-area sin crear una plantilla de áreas

La propiedad `grid-area` que aprendió en el último desafío se puede usar de otra manera. Si su grid no tiene una plantilla de áreas para hacer referencia, puede crear un área sobre la marcha para que un elemento se coloque así:

````
item1 {grid-area: 1/1/2/4; }
````
Esto está utilizando los números de línea que aprendió anteriormente para definir dónde estará el área para este elemento. Los números en el ejemplo anterior representan estos valores:

````
grid-area: línea horizontal para comenzar / línea vertical para comenzar / línea horizontal para terminar / línea vertical para terminar;
````

Entonces, el elemento en el ejemplo consumirá las filas entre las líneas 1 y 2, y las columnas entre las líneas 1 y 4.

----

Usando la propiedad `grid-area`, coloque el elemento con la clase `item5` entre las líneas horizontales tercera y cuarta y entre las líneas verticales primera y cuarta.

La clase `item5` debe tener una propiedad `grid-area` tal que esté entre la tercera y la cuarta línea horizontal y entre la primera y la cuarta línea vertical.

[Desafío #16](https://codepen.io/sebastiantorres86/pen/poJERNQ)

----
[Próxima Clase](https://github.com/sebastiantorres86/Curso-CSS-Grid/blob/master/17-funcion-repeat.md)