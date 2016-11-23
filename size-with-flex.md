Nuevas propieades para espacio, lo más común por defecto es usar:

`min-width: 0`

* #`flex-grow`

Nueva propiedad de espacio en flex, por defecto:

`flex-grow: 0;`

Asiganando el valor 1 ocupa el máximo espacio posible:

`flex-grow: 1;`

También es posible utilizarlo proprocinalmente, es decir en un contenedor **sin contenido** de 1000px sería:

`flex-grow: 1;` --> 250px

`flex-grow: 2;` --> 500px

`flex-grow: 1;` --> 250px

Se cálcula de manera proporcional.

*OjO* **Con contenido** se adapata dependiendo el contenido que tiene.

*OjO* Si queremos que las imagenes mantengan su tamaño original: 

##### `flex-shrink: 0`

---------------------------------------------- 

* #### *OjO* **Para definir anchos (min-width) en flex items**

Por defecto

#### `flex-basis: auto`

Se puede definir en %, px (absolute), em (relative), rm...

Combiar `flex-basis` y `flex-shrink nos permite hacer layouts homogenos, es decir la imagen ocupa lo máximo de 'flex-basis` tanto en horizontal como en vertical.

Hay que tener en cuenta:

```CSS
/* Intrinsic sizing keywords*/
flex-basis: fill;
flex-basis: max-content;
flex-basis: min-content;
flex-basis: fit-content;

/* Automatically size based on the flex item's content */
flex-basis: content;
```
------------------------------------------------------


* #### `align-self`
** Para alinear un item flex individual del resto:**

El valor por defecto es `align-self: strech`, `align-self` sobreescribe a `align-content`


Es útil para usarlo en column, para ello ver las diapositivas 73 y 74.

* #### `align-content`
**Usado para alinear los flex item wrapped**

