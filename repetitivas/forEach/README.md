# ForEach
El método forEach en Javascript itera sobre los elementos de una matriz(Array) y llama a la función proporcionada para cada elemento en orden.

Nota: forEach solo funciona en matrices. No ejecuta una función para una matriz sin ningún elemento.


En el siguiente código, el método forEach () llama a la función proporcionada para cada elemento de arr en orden. El elemento se utiliza para almacenar el valor actual y, como resultado, todos los elementos de la matriz se muestran en la consola uno por uno.

No se han pasado parámetros opcionales en este caso. El siguiente código utiliza parámetros opcionales.

```javascript

var arr = ['Wall-E', 'Up', 'Coco'];

arr.forEach(function(item) {
  console.log(item);
})

```
En este codigo podemos ver que ademas de imprimir el valor de nuestra matriz, tambien imprimimos su posicion en la matriz y la matriz completa

```javascript

var arr = [5,4,8,7];

arr.forEach(function(item,index,arr) {
  console.log("item: " + item + " posicion: " + index + " en la matriz: " + arr);
})

```