- Acordate que existe una función para saber si hay bolitas de un color determinado en el casillero;
- te dejamos el código de la solución anterior, lo único que tenés que cambiar es la **pregunta**.

```gobstones
procedure IrAlExtremo(direccion) {
  while (puedeMover(direccion)) {
    Mover(direccion)
  }
}
```