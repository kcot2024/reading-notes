#  Lista de Mitos y Verdades para Analizar

### ¿Qué diferencias fundamentales encuentras entre resolver un problema con programación imperativa y hacerlo con programación funcional?

Por ejemplo, para sumar los elementos de un array, la programación imperativa usa un bucle y una variable acumuladora, mientras que la programación funcional emplea el método reduce, evitando la mutabilidad.


### ¿Cuándo es más ventajoso usar funciones puras y cuándo no?
Es bueno cuando por ejempplo se tiene que hacer calculos matematicos y no es  ventanjosos cuando hay interacciones con bases de datos
### Rol de las funciones de orden superior (map(), filter(), find()) en la calidad y legibilidad del código

Evitan bucles explícitos, haciendo el código más declarativo y fácil de entender.
Mejoran la reutilización al separar la lógica de iteración del procesamiento de datos.
Ejemplo de mejora en legibilidad:

### ¿Por qué la programación funcional facilita pruebas unitarias y debugging?
La programación funcional facilita las pruebas unitarias y el debugging porque usa funciones puras,
### ¿Cómo integrar programación funcional en proyectos imperativos?
Usar métodos funcionales nativos (map, reduce, filter, every, etc.).
Introducir funciones de orden superior para reemplazar bucles for con transformaciones declarativas.
