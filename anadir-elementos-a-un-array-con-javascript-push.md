## Añadir elementos a un array con Javascript push

Lo primero que hacemos es crear una variable llamada *nombres* y la llenamos con nombres propios:

`var nombres = ["Luís", "Alberto"]`.

Para comprobar el array, lo que hacemos es mostrar por pantalla el array:

~~~
for (name in nombres) {
    document.write(nombres[name]+)
}
~~~

Vemos que en pantalla salen los nombres:

~~~
Luís
Alberto
~~~

Vamos a usar el método *JavaScript push*. Recibe como parámetro el elemento que queremos insertar:

~~~
nombres.push("Juan");
nombres.push("María");
nombres.push("Irene");
nombres.push("Víctor");
~~~

> El método Javascript push no comprueba si el elemento a insertar en el array existe previamente. Siempre lo inserta.

Si volvemos a recorrer el array con el código explicado arriba veremos que la salida es la siguiente:

`Juan`
`María`
`Irene`
`Víctor`