# Ejemplos practicos sobre programación funcional en JavaScript

Existen muchos paradigms de programación, pero los mas conocidos son el paradigma procedural, orientación a objetos y la programación funcional. Muchas personas que intentan aprender programación funcional terminan fracasando  o rindiendose por un simple motivo, la jerga matematica que existe detras del mismo.

Por ese motivo me propuse hacer este repositorio.
El mismo esta repleto de codigo de ejemplo donde se muestran casos de usos útiles
de estos principios matematicos y como podemos aplicarlos en nuestro dia a dia.

Expero les sea de utilidad :)

#### Todos los ejemplos usaran la syntaxis de ES2015 (Javascript 2015).

* [Aridad](#aridad)



La aridad se refiere a la cantidad de argumentos que acepta una función.
Tambien se conoce como binaria (si tiene aridad 2), unaria (si es de aridad 1),
o variadic si es una función que toma un numero variable de argumentos.
Ej:
```javascript
   const incrementar = (x) => x + 1
   const suma = (x,y) => x + y
```
[descargar ejemplo](https://github.com/idcmardelplata/programacion-funcional-javascript-ejemplos-practicos/ejemplos/aridad.js)

La función suma se dice que es de **aridad** 2 puesto que acepta 2 argumentos, y la función incrementar es de aridad 1 puesto que solamente
tiene un argumento, si la funcion tomara `n` argumentos, significaria que seria de aridad `n`.


Este documento es un papper donde se pretende ir subiendo ejemplos practivos de codigo. Si tienes alguna mejora o correccion te animo a [Colaborar!](https://github.com/idcmardelplata/programacion-funcional-javascript-ejemplos-practicos/graphs/contributors)!.
