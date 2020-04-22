# JavaScript if else y else if
La instrucción if / else ejecuta un bloque de código si una condición especificada es verdadera. Si la condición es falsa, se puede ejecutar otro bloque de código. La declaración if / else es parte de las declaraciones "condicionales" de JavaScript, que se utilizan para realizar diferentes acciones en función de diferentes condiciones.

Use if para especificar un bloque de código que se ejecutará, si una condición especificada es verdadera.
Use else para especificar un bloque de código que se ejecutará, si la misma condición es falsa.
Use else if para especificar una nueva condición para probar, si la primera condición es falsa.

https://www.w3schools.com/js/js_if_else.asp

## Formas de Usarlo

```javascript
var nombre = 'John Do';
if (nombre) {
    // Este codigo se ejecuta si la condicion es verdadera
    console.log(nombre)
    // ouput: John Do
}
```

```javascript
var condicionFalsa = 0;
if (condicionFalsa) {
} else {
    // Este codigo se ejecuta si la condicion es falsa
}
```

```javascript
var condicionUno = 0;
var condicionDos = 'John Do';
if (condicionUno) {
    // Este codigo se ejecuta si la primera condicion es verdadera.
} else if(condicionDos) {
    // Este codigo se ejecuta si la segunda condicion es verdadera.
} else {
    // Este codigo se ejecuta si ninguna de las dos condiciones son verdadera.
}
```

## Logical Operators
Los operadores de comparación se utilizan en declaraciones lógicas para determinar la igualdad o diferencia entre variables o valores.

<table class="w3-table-all notranslate">
<tbody><tr>
<th style="width:12%">Operator</th>
<th>Description</th>
<th>Comparing</th>
<th>Returns</th>
</tr>
<tr style="background-color:#f5f5f5;">
<td rowspan="3">==</td>
<td rowspan="3">equal to</td>
<td>x == 8</td>
<td>false</td>
</tr>
<tr style="background-color:#f5f5f5;">
<td>x == 5</td>
<td>true</td>
</tr>
<tr style="background-color:#f5f5f5;">
<td>x == "5"</td>
<td>true</td>
</tr>
<tr style="background-color:#ffffff;">
<td rowspan="2">===</td>
<td rowspan="2">equal value and equal type</td>
<td>x === 5</td>
<td>true</td>
</tr>
<tr style="background-color:#ffffff;">
<td>x === "5"</td>
<td>false</td>
</tr>
<tr style="background-color:#f5f5f5;">
<td>!=</td>
<td>not equal</td>
<td>x != 8</td>
<td>true</td>
</tr>
<tr style="background-color:#fff;">
<td rowspan="3">!==</td>
<td rowspan="3">not equal value or not equal type</td>
<td>x !== 5</td>
<td>false</td>
</tr>
<tr style="background-color:#fff">
<td>x !== "5"</td>
<td>true</td>
</tr>
<tr style="background-color:#fff">
<td>x !== 8</td>
<td>true</td>
</tr>
<tr style="background-color:#f5f5f5">
<td>&gt;</td>
<td>greater than</td>
<td>x &gt; 8</td>
<td>false</td>
</tr>
<tr style="background-color:#ffffff;">
<td>&lt;</td>
<td>less than</td>
<td>x &lt; 8</td>
<td>true</td>
</tr>
<tr style="background-color:#f5f5f5;">
<td>&gt;=</td>
<td>greater than or equal to</td>
<td>x &gt;= 8</td>
<td>false</td>
</tr>
<tr style="background-color:#ffffff;">
<td>&lt;=</td>
<td>less than or equal to</td>
<td>x &lt;= 8</td>
<td>true</td>
</tr>
</tbody></table>

<table class="w3-table-all notranslate">
<tbody><tr>
<th style="width:12%">Operator</th>
<th>Description</th>
<th>Example</th>
</tr>
<tr>
<td>&amp;&amp;</td>
<td>and</td>
<td> (x &lt; 10 &amp;&amp; y &gt; 1) is true</td>
</tr>
<tr>
<td>||</td>
<td>or</td>
<td>(x == 5 || y == 5) is false</td>
</tr>
<tr>
<td>!</td>
<td>not</td>
<td> !(x == y) is true</td>
</tr>
</tbody></table>


## Ejemplos

```javascript
var condicionUno = 'John Do';
var condicionDos = 'John Do';
if (condicionUno == condicionDos) {
    // Este codigo se ejecuta si la condicion uno es igual que la condicion dos.
}
```

```javascript
var condicionUno = 10;
var condicionDos = 5;
if (condicionUno > condicionDos) {
    // Este codigo se ejecuta si la condicion uno es mayor que a la condicion dos.
}
```

```javascript
var condicionUno = true;
var condicionDos = false;
if (condicionUno != condicionDos) {
    // Este codigo se ejecuta si la condicion uno es distinta que a la condicion dos.
}
```

```javascript
var condicionUno = false;
if (!condicionUno) { // El operado ! invierte el valor de false a true o de true a false.
    // Este codigo se ejecuta si la condicion uno es verdadera.
}
```