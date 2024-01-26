Tailwiind ya utiliza box-sizing: border-box, no lo hace CSS por defecto por temas de retrocompatibilidad.

Por defecto los elementos se posicionan de manera estática.

Colocando inset 0 y margin auto se puede centrar un div, teniendo position relative, y position absolute en el elemento padre.

La pagina no es en 2d, sino que hay como profundidad, es ahi donde entra el z-index.
La lista para el contezto de apilamiento se encuentra en MDN.

Display block los alinea uno sobre otro, es el que tiene por defecto un grid.
Display inline significa que se va a comportar como texto, de izquieda a derecha (No es correcto que siempre fila es de izquierda a derecha).

Display flex extablece como tiene que funcionar el contenedor de acuerdo a sus hijos (Se coloca en el contenedor)

En Flex se trabaja solamente en un eje, ya sea en filas o en columnas.

con flex ditection no wrap, basis auto y valores 1 en el grow y shrink, los elementos se ajustan al contenido (texto)

Con los valores anteriores, pero con un valor 0 en flex-basis se puede hacer que todos los elementos tengan el mismo tamaño sin importar el contenido (Lo mismo que flex:1)

El flex: 1 tambien puede usarse como medida relativa, colocandolo al padre y si se desea por ejemplo que uno tenga el doble del tamaño que los demás, se coloca flex:2.

Se puede colocar la propiedad order para cambiar el orden de los elementos, usualmente se usa en footers responsive.

[Juego para aprender FlexBox](https://flexboxfroggy.com/)
