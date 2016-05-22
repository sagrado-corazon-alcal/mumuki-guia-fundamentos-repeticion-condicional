Todo muy lindo esto del `while`, pero ¿qué pasa si la pregunta **siempre es verdadera**? Veamosló con un ejemplo:

```puppet
procedure HastaElInfinito() {
  while (puedeMover(Este)) {
    Poner(Rojo)
  }
}
```

> ¿Cuándo terminará ese procedimiento? Averigualo: copiá el código en el editor y fijate qué hace.