# Ejemplos prácticos sobre programación funcional en JavaScript

Existen muchos paradigmas de programación, pero los más conocidos son el paradigma procedural, orientación a objetos y la programación funcional. Muchas personas que intentan aprender programación funcional terminan fracasando  o rindiéndose por un simple motivo, la jerga matemática que existe detrás del mismo. Por ese motivo me propuse hacer este repositorio. El mismo está repleto de código de ejemplo donde se muestran casos de uso útiles de estos principios matemáticos, y como podemos aplicarlos en nuestro día a día.

Espero les sea de utilidad :)

**Nota:** Todos los ejemplos usarán la sintaxis de ES2015 (Javascript 2015).


## Listado de ejemplos

- [Aridad](#aridad)


### Aridad<a name="aridad"></a>

La aridad se refiere a la cantidad de argumentos que acepta una función.
También se conoce como binaria (si tiene aridad 2), unaria (si es de aridad 1),
o variadic si es una función que toma un número variable de argumentos.

Ej:
```js
  const incrementar = x => x + 1
  const suma = (x, y) => x + y
```

[Descargar ejemplo](https://github.com/idcmardelplata/programacion-funcional-javascript-ejemplos-practicos/blob/master/ejemplos/aridad.js)

La función suma se dice que es de **aridad 2**, puesto que acepta 2 argumentos, y la función incrementar es de **aridad 1**, puesto que solamente
tiene un argumento. Si la función tomara `n` argumentos, significaría que sería de aridad `n`.


## Acerca de este documento

Este documento es un papper donde se pretende ir subiendo ejemplos prácticos de código. 
Si tienes alguna mejora o corrección te animo a [¡Colaborar!](https://github.com/idcmardelplata/programacion-funcional-javascript-ejemplos-practicos/graphs/contributors)
