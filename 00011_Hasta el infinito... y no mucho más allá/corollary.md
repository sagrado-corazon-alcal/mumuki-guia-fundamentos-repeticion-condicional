Ups... el procedimiento **no termina** nunca. :confused:

En este ejemplo, ninguna de las **acciones** que están dentro de la repetición contribuyen a que esta termine: debería haber algún comando que provoque que el cabezal se mueva hacia el Este, logrando que `puedeMover(Este)` en algún momento sea falso. ¡Siempre tenés que asegurarte de que cada paso de la repetición **se acerca** hacia el final!

Un gran poder conlleva una gran responsabilidad: ¡mucho cuidado cuando uses un `while`!