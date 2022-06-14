# Curso-Profesional-CSS-GridLayout

...

### Técnicas de alineamiento antes de CSS Grid: margin y line-height


***

<center>Veremos 4 técnicas de alineamiento</center>

***

- `margin` 
- `line-height`
- `table-cell`
- `positions`

***

<center>Propiedades margin</center>

***

- `margin-top` 
- `margin-right`
- `margin-right`
- `margin-left`

> Ejemplo:  
margin-top: 10px;  
margin-right: 15px;  
margin-bottom: 20px;  
margin-left: 25px;

Otra forma de realizarlo directamente.  
> Ejemplo:  
margin: 10px 15px 20px 25px;

### Técnicas de alineamiento antes de CSS Grid: table-cell y positions

***

<center>Técnica positions</center>

***

- `position: relative` 
- `position: absolute`
- `top`
- `right`
- `bottom`
- `left`
- `transform: translate()`  

- Posiciones

Posicionado de acuerdo al flujo normal

| static | relative | absolute | fixe |
| ----- | --- | ---- | --- |
|   ✓  |  ✓  |   X   |  X  |

Su posicion final la determinan top, right, bottom, y left

| static | relative | absolute | fixe |
| ----- | --- | ---- | --- |
|   X  |  ✓  |  ✓    |  ✓  |

Crea un nuevo contexto de apilamiento

| static | relative | absolute | fixe |
| ----- | --- | ---- | --- |
|   X  |  ✓  |  ✓    |  ✓  |

### Position: absolute
- Distancia entre contenedor y elemento.

### Position: relative
- Distancia entre su posicion inicial y la posicion final

> Ejemplo:  
top: longitud | porcentaje | auto | inherit;

- Longitud: px,em
- Porcentaje: %
- Auto: valor por defecto
- inherit: hereda del padre

### Transform: translate()

- Nos ayuda a organizar nuestra coordenadas ( x, y )

> Ejemplo:  
transform: none | transform-functions | initial | inherit;