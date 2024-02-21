# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/oWmOqxIanjk?si=5-d7lzG1Y7dDdOUq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



`<nav></nav>`  se utiliza para definir una sección de navegación en un documento web. Contiene enlaces o menús que permiten a los usuarios desplazarse o acceder a diferentes partes del sitio web o a otras páginas relacionadas

`<i></i>` Muestra el texto marcado con un estilo en cursiva o italica

Comparador logico en css  `>`   es utilizado en CSS para seleccionar todos los **elementos que sean directamente descendientes de otro**, es decir, que sean hijos directos de un determinado elemento padre 

Por ejemplo, la expresión:

```css
div > p
```

Seleccionará todos los **elementos `p` que sean descendientes directos de un div** , mientras que la siguiente expresión:

```css
div p
```

Seleccionará **todos los elementos `p` dentro del `div`**, incluso los que estén anidados en niveles más profundos. 

`transition: s;` Permite definir la transición entre dos estados de un elemento. 

`hover:` coincide cuando el usuario interactúa con un elemento con un dispositivo señalador, pero no necesariamente lo activa. Generalmente se activa cuando el usuario se desplaza sobre un elemento con el cursor, se suele usar con la propiedad predefinida de transition para indicar que se active cuando se pasa el mouse

`nth-child()` coincide con elementos según los índices de los elementos en la lista secundaria de sus padres. En otras palabras, el selector selecciona elementos secundarios según su posición entre todos los elementos hermanos dentro de un elemento principal

`@media` asocia un grupo de declaraciones anidadas, en un bloque CSS delimitado por llaves, con una condición definida por un media query

Muchas características de medios son *características de rango*, lo que significa que pueden tener el prefijo "min-" o "max-" para expresar restricciones de "condición mínima" o "condición máxima". Por ejemplo, este CSS aplicará estilos solo si el ancho del viewport de su navegador es igual o menor que 1250px:

CSSCopy to Clipboard

```css
@media (max-width: 1250px) {
  /* … */
}
```

Para limitar los estilos a los dispositivos con una pantalla, puede encadenar las características de medios al tipo de medios `screen`:

CSSCopy to Clipboard

```css
@media screen and (min-width: 30em) and (orientation: landscape) {
  /* … */
}
```