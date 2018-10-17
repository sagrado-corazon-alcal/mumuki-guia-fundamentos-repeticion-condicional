Comencemos con un problema que planteamos anteriormente y que ya solucionamos :tada:.

¿Qué pasaba cuando queríamos ir hasta un extremo del tablero? Como no sabíamos cuántas veces teníamos que movernos, no se podía usar `MoverN`.
Por suerte ya había un procedimiento creado para eso: `IrAlBorde(direccion)`.

Hagamos el nuestro propio, al cual llamaremos `IrAlExtremo(direccion)`, para ver cómo es que funciona :eyes:.

Como ya se sabe, existe la función `puedeMover(direccion)` que nos indica si el cabezal puede moverse en una cierta dirección. Con esto y un poco de imaginación, podríamos pensar una forma de repetición que haga lo siguiente:

1. Pregunte si el cabezal se puede mover en la dirección deseada;
2. mueva el cabezal en la dirección deseada;
3. vuelva al paso 1, hasta que ya no pueda moverse.

Interesante, ¿no? :smirk: Exactamente esa es la forma de resolverlo, y (por esta vez) va de regalo :gift::

```gobstones
procedure IrAlExtremo(direccion) {
  while (puedeMover(direccion)) {
    Mover(direccion)
  }
}
```

> Escribí nuestra versión de `IrAlExtremo` en el editor y enviala.