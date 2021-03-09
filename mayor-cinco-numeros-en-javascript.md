## Mayor de cinco números en Javascript

Lo primero es crear una variable que contiene un array con 5 números cualesquieras:

`var numeros = [3, 5, 2, 9, 12];`.

Ahora declaramos otra variable donde avergará el número mayor de los 5:

`numeroMayor = numeros[0];`.
Como vemos los accesos a los elementos de un array se hacen mediante el operador corchete `[]`.

Vamos a recorrer el array mediante un bucle *for*. Es para comprobar en el array cual de esos números son el mayor. La sentecia es la siguiente:

~~~
for (x=1; x > numeroMayor) {
    numeroMayor = numeros[x];
}
~~~

Para saber si salio todo bien nos resta hacer un *console.log* en el navegador:

`console.log('El número mayor es: ' + numeroMayor')`.