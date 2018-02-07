En determinado punto del viaje, Alex tiene que escalar una montaña. Como ya dijimos antes, a sus paredes la vamos a representar con bolitas azules. Las montañas pueden tener diferentes tamaños y formas, por ejemplo:

<gs-board>
  GBB/1.0
    size 3 4
    cell 1 0 Azul 1
    cell 1 1 Azul 1
    cell 2 0 Azul 1
    cell 2 1 Azul 1     
    cell 2 2 Azul 1     
    head 0 0
</gs-board>

Vamos a hacer un procedimiento que le sirva al viajero para escalar **cualquier** montaña, asumiendo que la misma siempre va a estar **al Este** de su ubicación. La escalada la vamos a hacer por etapas, en cada etapa hay que subir hasta el siguiente descanso; en el ejemplo, el primer descanso está en la posición (1, 2).

> Implementá el procedimiento `TreparHastaDescanso()`, que deje a nuestro amigo en el primer descanso que haya en la montaña.