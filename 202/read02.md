# Lista de Mitos y Verdades para Analizar
### Flexbox solo funciona para diseños horizontales.
Mito, Flexbox funciona tanto en dirección horizontal (flex-direction: row) como en vertical (flex-direction: column).

### flex-wrap permite que los elementos se ajusten automáticamente en múltiples líneas.
Verdad, flex-wrap: wrap hace que los elementos se distribuyan en varias líneas si no caben en una sola.
### Con Flexbox, ya no es necesario usar media queries.
Mito, Aunque Flexbox permite diseños flexibles, las media queries siguen siendo necesarias para ajustar estilos según el tamaño de pantalla.
### justify-content: space-between distribuye los elementos dejando espacios iguales entre ellos.
Mito, space-between coloca espacio igual entre los elementos, pero no en los extremos. Para espacios iguales en ambos lados, se usa space-around o space-evenly.
### Flexbox no es adecuado para crear layouts completos.
Mito, Aunque CSS Grid es más potente para estructuras complejas, Flexbox puede ser suficiente para muchos layouts, especialmente cuando se requiere alineación dinámica.
### La IA puede generar ejemplos de Flexbox, pero siempre deben validarse.
Verdad, La IA puede generar código, pero es recomendable revisarlo, ya que puede contener errores o no seguir las mejores prácticas.
### flex-grow permite que los elementos crezcan para ocupar espacio adicional.
Verdad, flex-grow define cuánto debe crecer un elemento en relación con los demás dentro del contenedor flex.
### Usar demasiados <div> afecta la semántica del documento.
Verdad, El uso excesivo de <div> sin propósito semántico puede hacer que el código sea menos accesible y más difícil de mantener.
### Flexbox no funciona bien en navegadores antiguos.
Verdad, Flexbox no es compatible con versiones antiguas de IE y requiere prefijos en ciertos navegadores.
### La propiedad align-items controla la alineación vertical de los elementos.
Verdad, align-items define la alineación en el eje transversal, que en flex-direction: row es vertical, y en flex-direction: column es horizontal.