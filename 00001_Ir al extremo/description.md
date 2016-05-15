Comencemos con uno de los problemas que planteamos recién: escribir un procedimiento que mueva el cabezal hasta un extremo del tablero. 

Este procedimiento debería funcionar de forma tal que si yo hago `IrAlExtremo(Este)`, el cabezal se posiciona _"lo más al Este"_ que pueda, conservando la fila en la que está (y de igual forma para cualquiera de las otras direcciones).

Probablemente tu primera idea sea intentar algo con `MoverN`, pero como ya dijimos eso no sirve; no tenemos forma de saber cuántas veces hay que moverse: podrían ser 3, 12 o ninguna.

Lo que sí sabemos es que existe una función `puedeMover(direccion)` que nos indica si el cabezal puede moverse en una cierta dirección. Con esto y un poco de imaginación, podríamos pensar una forma de repetición que haga lo siguiente:

1. Pregunte si el cabezal se puede mover en la dirección deseada.
2. Mueva el cabezal en la dirección deseada.
3. Vuelva al paso 1, hasta que ya no pueda moverse.

Bueno, exactamente esa es la forma de resolverlo, y (por esta vez) va de regalo: :gift:

```puppet
procedure IrAlExtremo(direccion) {
  while (puedeMover(direccion)) {
    Mover(direccion)
  }
}
```

> Copiá nuestra versión de `IrAlExtremo` en el editor y enviala.