## CSS GRID ###

**Grid Container:** Elemento padre que va a tener puesto un nuevo tipo de display (display: grid). Nos permite colocar otras propiedades para manipular nuestro layout.

**Grid Item:** Son elementos que vamos a manejar. Seran filas o columnas que vamos a poder manejar a nuestro gusto.


> Nota: son hijos directos de grid (Grid Container).

**Grid Line:** Lineas divisorias horizontales y verticales. <br>
**Grid Track:** Espacio entre dos líneas adyacentes(filas y columnas). <br>
**Grid Cell:** Celdas, espacio en dos filas adyacentes y 2 columnas adyacentes. <br>
**Grid Area:** Espacio rodeado por 4 grid lines


## Propiedades ##

> **grid-template-columns:** Define el número de columnas en un grid layout así como el tamaño de cada columna. 
<br>Con el siguiente ejemplo creamos 3 columnas de 200px de ancho cada una, cabe destacar que podemos asignar cualquier tamaño a cualquiera de las columnas y utilizar cualquier unidad de medida. <br>
> **Ejemplo:** `grid-template-columns: 200px 200px 200px;` 


> **grid-template-rows:** Define el nombre de las líneas y las funciones de tamaño de línea de grid rows.
<br>Con el siguiente ejemplo indicamos el tamaño de cada una de nuestras filas, en este caso solo definimos la altura para la primera (100px) y segunda (200px) fila. <br>
> **Ejemplo:** `grid-template-rows: 100px 200px;`

> **grid-template:** Podemos definir filas y columnas en la misma linea.
<br>**Ejemplo:** `grid-template: 100px 200px / 30% 50% 20%;`

> **grid-column-gap:** Permite definir el espacio entre columnas.
<br>**Ejemplo:** `grid-column-gap: 20px;`

> **grid-row-gap:** Permite definir el espacio entre filas.
<br>**Ejemplo:** `grid-row-gap: 20px;`

> **grid-gap:** Permite definir el espacio entre filas y columnas en una misma linea.
<br>**Ejemplo:** `grid-gap: 30px 10px;`

> **fr:** Unidad de medida que representa una fracción. <br>
> **repeat(number, value):** Permite repetir una valor un determinado número de veces. <br>
> **minmax(min, max):** Permite definir un mínimo y máximo. <br>
> **grid-template-areas:** Especifica nombres para cada una de las grid areas. <br>
> **grid-column-start:** Definimos en que linea empieza. <br>
> **grid-column-end:** Definimos en que linea termina. <br>
> **grid-column:** Definimos en que linea de las columnas empieza y donde termina. <br>
> **grid-row:** Definimos en que linea de las filas empieza y donde termina.

### Links de Interes ###

[CSS Grid Layout - MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout)
<br>
[Complete Guide to Grid - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
<br>
[CSS Grid Layout Module Level 1 - W3C](https://www.w3.org/TR/css-grid-1/)
<br>
[CSS Grid Tutorial](https://www.quackit.com/css/grid/tutorial/)
<br>
[Explicit vs Implicit Grid](https://www.quackit.com/css/grid/tutorial/explicit_vs_implicit_grid.cfm)
<br>
[CSS Grid Examples](https://www.quackit.com/css/grid/examples/)