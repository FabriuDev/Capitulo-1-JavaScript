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
# Operadores (Intermedio)

---

## Operadores de Comparacion

`Los operadores de comparacion comparan dos expresiones y devuelven un valor Boolean que representa relacion de sus valores`

- Ejemplo de igualdad (Pregunta si son el mismo dato):

```js
let numero1 = 10;
let numero2 = 10;

document.write(numero1 == numero2) true
```

- Ejemplo de Desigualdad

```js
let numero1 = 23;
let numero2 = 13;

document.write(numero1 != numero2) true
```

- Ejemplo de Igual Estricta (Todo Igual)

```js
let numero1 = 23;
let numero2 = 23;

document.write(numero1 === numero2) true
```

- Ejemplo de Estrictamente diferente (Todo diferente)

```js
let numero1 = 23;
let numero2 = '23';

document.write(numero1 !== numero2) true
```

- Ejemplo de mayor a

```js
let num1 = 20;
let num2 = 20;

document.write(num1 > num2) false
```

- Ejemplo de menor a

```js
let num1 = 15;
let num2 = 20;

document.write(num1 < num2) true
```

- Ejemplo de mayor o igual a

```js
let num1 = 20;
let num2 = 20;

document.write(num1 >= num2) true
```

- Ejemplo de menor o igual a

```js
let num1 = 10;
let num2 = 20;

document.write(num1 <= num2) false
```

---

## Operadores Logicos

`Los operadores logicos nos devuelven un resultado a partir de que se cumpla (o no) una condicion, su resultado es booleano, y sus operandos son valores logicos o asimilables a ellos.`

- Ejemplo de los 3 operadores logicos:

```js
let valor1 = true;
let valor2 = true;

let resultado = valor1 && valor2;
let resultado2 = valor1 || valor2;
let resultado3 = !valor1;

document.write()
```

    Significado de &&: 
    false + true = false
    true + true = true
    false + false = false
---
    Significado de ||:
    false + true = true
    false + false = false
    true + true = true
---
    Significado de !valor:
    hace que el valor cambie de forma opuesta a partir del signo !
---
### Ejercicios

```js
num1 = 12;
num2 = 24;
num3 = 25;
num4 = 92;
num5 = 91;

op = (num1 < num2 || num2 < num3) && (!(num1 && num5 != num3));

document.write(op)
```
---
# Condicionales
---
### Ejemplo de condionales:

```js
let nombre = 'fabrizio';
let apellido = 'rodriguez'

// se utiliza un solo if
if (nombre == 'fabrizio' && apellido == 'rodriguez') { // si la condicion se cumple, se ejecuta la accion. 
    alert(`tu nombre es ${nombre} ${apellido}`);
}
//se pueden utilizar muchos else if
else if (apellido == 'rodriguez') { // si la condicion se cumple, se ejecuta la accion.
    alert(`tu apellido es ${apellido}`);
}
// se utiliza un solo else
else { // si nada de lo anterior se cumple, se utiliza else.
    alert(`Usuario no disponible`);
}
```
---
# Capitulo 1 (Crear Soluciones)
---

- Cofla va a la heladeria y quiere comprar un helado + saber cuanto dinero le sobra!

```js
dineroCofla = prompt('Cuanto dinero tenes Cofla?');//variable
dineroCofla = parseInt(dineroCofla);//esto sirve para pasar a entero una cadena de texto

if (dineroCofla >= 0.6 && dineroCofla < 1) {// se cumple la condicion y se usa un solo if
    alert('cofla, Comprate el helado de agua');
    alert('y te sobran ' + (dineroCofla - 0.6));//para encadenar esta operacion, necesitamos (parentesis)
}

else if (dineroCofla >= 1 && dineroCofla < 1.6) {// se cumple la condiciony se pueden usar muchos else if
    alert('cofla, Comprate el helado de crema');
    alert('y te sobran ' + (dineroCofla - 1));
}

else if (dineroCofla >= 1.6 && dineroCofla < 1.7) {
    alert('cofla, Comprate el helado de Tercera marca');
    alert('y te sobran ' + (dineroCofla - 1.6));
}

else if (dineroCofla >= 1.7 && dineroCofla < 1.8) {
    alert('cofla, Comprate el helado de Segunda marca');
    alert('y te sobran ' + (dineroCofla - 1.7));
}

else if (dineroCofla >= 1.8 && dineroCofla < 2.9) {
    alert('cofla, Comprate el helado de Primera marca');
    alert('y te sobran ' + (dineroCofla - 1.8));
}

else if (dineroCofla >= 2.9) {
    alert('cofla, comprate un 1/4 de helado');
    alert('y te sobran ' + (dineroCofla - 2.9));
}

else {
    alert('Lo siento cofla! no te alcanza para nada')//si nada de lo anterior se cumple, sale esto
}
```
---
