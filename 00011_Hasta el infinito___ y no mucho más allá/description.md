Todo muy lindo esto del `while`, pero ¿qué pasa si la pregunta **siempre es verdadera**? Veamoslo con un ejemplo:

```gobstones
procedure HastaElInfinito() {
  while (puedeMover(Este)) {
    Poner(Rojo)
  }
}
```

> ¿Cuándo terminará ese procedimiento? Averigualo: escribí el código en el editor y fijate qué hace.