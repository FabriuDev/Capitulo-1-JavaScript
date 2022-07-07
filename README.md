# Capitulo-1-JavaScript
---
# Variables
---
- Usos para una variable:

```javascript
string = "cadena de texto";
number = 10 (numeros);
boolean = true/false;
```

- existen 3 tipos de variables para usar:

```javascript
var nombre = "Fabrizio R.";
let edad = 18;
const nacionalidad = "Argentino";
```

>**var**: es una variable que abarca todo el bloque, se puede modificar
>**let**: abarca contenido en un bloque especifico porque tiene menos alcance, se puede modificar
>**const**: es una variable constante, es decir que no se puede modificar, ya que es inicializada una sola vez
---
- Tipos de datos:

>**Undefined:** es una variable **no definida**, hasta que se le otorgue un valor.
>**Null**: es una variable **no definida** pero **de forma adrede**.
>**NaN**: es cuando utilizamos texto en una operacion numerica o viceversa.
>**Scope**: es hasta donde llega la variable en especifico, afuera de su bloque no existe.
---
- Prompt

**Prompt es una funcion que te pide un dato de forma alerta, este dato se transforma en el mismo que coloco el usuario.**

>es decir si el usuario puso "Perro amarillo" en la cadena de texto, ahora el prompt contiene el dato de "Perro amarillo"
**Ejemplo:** 

```javascript
let nombre = prompt("Introduzca su nombre aqui")
alert("Bienvenido " + nombre)
```

- Ahi lo que hicimos fue practicamente usar la  variante "nombre" con el contenido prompt que a su misma vez contiene lo que el usuario puso, es decir su nombre.

---
# Operadores
---
    Operadores de Asignacion
>Un operador de asignacion asigna un valor al **operando de la izquierda** basado en el valor **del operando de la derecha**

- Asignacion:  
  - x = y
- Asignacion de adiccion: 
  - x += y 
- Asignacion de Sustraccion: 
  - x -= y 
- Asignacion de Multiplicacion: 
  - x *= y
- Asignacion de Division: 
  - x /= y
- Asignacion de Resto: 
  - x %= y
- Asignacion de Exponenciacion: 
  - x **= y
- Asignacion de Desplazamiento a la Izquierda:
  -  x <<= y
- Asignacion de Desplazamiento a la Derecha:
  - x >>= y
- Asignacion sin Signo de Desplazamiento a la Derecha:
  - x >>>= y
- Asignacion AND: 
  - x &= y
- Asignacion XOR: 
  - x ^= y
- Asignacion OR: 
  - x |= y

---


    Operadores Aritmeticos

>De esta manera se usan los operadores aritmeticos, mira los siguientes ejemplos.

- Adiccion
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1 + num2;//se suman ambas variables

alert(resultado)
```
- Decremento
```Javascript
let num1 = 10;
let num2 = 5;

num1--;

resultado = num1;//no necesita de la otra variable

alert(resultado)
```
- Division
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1 / num2;//necesita del otro numero para dividirse

alert(resultado)
```
- Exponenciacion
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1**2;//hay que asignarle una potencia(al cuadrado, al cubo, etc)

alert(resultado)
```
- Incrementar
```Javascript
let num1 = 10;
let num2 = 5;

num1++;

resultado = num1;//no necesita de otro numero para operar

alert(resultado)
```
- Multiplicar
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1 * num2;//sirve para multiplicar las dos numeros

alert(resultado)
```
- Resto
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1&num2;//Sirve para encontrar el resto de la operacion

alert(resultado)
```
- Substraccion
```Javascript
let num1 = 10;
let num2 = 5;

resultado = num1 - num2;//sirve para restar el resultado

alert(resultado)
```
- Negacion Unaria
```Javascript
let num1 = 10;
let num2 = 5;

resultado = -num1;//Sirve para invertir el resultado a negativo

alert(resultado)
```
---
