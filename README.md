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
# Arrays
---

- un array es un arreglo, es decir que un arreglo contiene mas cualidades que por ejemplo una variable, es mucho mas detallado y complejo.

- un array puede ser una caja de te, que adentro contiene bolsitas de te, y esas bolsitas de te son una diferente a la otra, de tal manera que tambien estan ordenadas de diferente forma, etc.


`Ejemplo de array`

```js
let frutas = ['manzana','banana','pera',6,'mango',22];//se colocan entre corchetes y de forma separada por comillas.

document.write(frutas[0,1,6])//se colocan corchetes con el lugar de cada elemento (empezando siempre desde el cero)
```

`Ejemplo de array Asociativo`

```js
let pc = {
    nombre: 'La Poderosa'
    procesador: 'Ryzen 5'
    ram: '16GB'
    espacio: '500GB'
};

let pcCompleta = `el nombre de mi pc es <b>${nombre}</b> <br>
                el procesador es: <b>${procesador}</b> <br>
                la memoria ram es: <b>${ram}</b> <br>
                el espacio es de: <b>${espacio}</b>`;

document.write(pcCompleta);
```
---
# Bucles e interaccion (Parte 1)

`En JavaScript los bucles (loops) son utilizados para realizar tareas repetitivas con base en una condición. Las condiciones típicamente devuelven true (verdadero) o false (falso) al ser evaluados. El bucle continuará ejecutándose hasta que la condición devuelva false`

- existen todos estos tipos de bucles e interacciones:
  - while
  - do while
  - for
  - for on
  - for of
  - break
  - label
  - continue


#### Ejemplo de while:

```js
let numero = 0;//asigna una variante

while (numero < 5) {//se ejecuta la accion si se cumple la condicion
    numero++;//agrega un +1 al numero
    document.write(numero + "<br>");//agrega la variante mas un espacio en linea por cada numero
}
```
#### Ejemplo de do while:

```js
let numero = 0;//asigna una variable

do {//siempre se ejecuta
    document.write(numero);//muestra el resultado en pantalla
    numero++;//agrega un +1 al numero
}

while (numero < 5) {//se ejecuta de forma infinita si la condicion es true
}
```

#### Ejemplo de while con break:

```js
let numero = 0;//asigna una variable

while (numero < 1000) {//si numero es menor a 1000 ejecuta la accion
    numero++;//agrega un +1 al numero
    document.write(numero + "<br>");
    if (numero == 10){
        break;//formamos un if para que break se ejecute y se frene en el numero 10 y siga el programa
    }
}
```

#### Ejemplo de for:

- for tiene 3 caracteristicas, primero se coloca la declaracion, segundo la condicion y al final el incremento o el decremento.

```js
for (let i = 0; i < 6; i++){//primero creamos la variable i y la igualamos a 0, luego creamos la condicion i < 6 que es true, y al final agregamos un +1.
    document.write(i + "<br>");
}
```
#### Ejemplo de for con break:

```js
for (let i = 0; i < 20; i++){
    if (i == 12){//termina el bucle en el numero 12, es decir que no lo muestra
        break;
    }
    document.write(i + "<br>");
}
```

#### Ejemplo de for con continue:

```js
for (let i = 0; i  5; i++){
    if (i == 3){//hace que se saltee el 3 y continue hasta el 5
        continue;
    }
    document.write(i + "<br>");
}
```
---
# Bucles e Interaccion (Parte 2)
---

        los bucles for in, for of y sentencia label

- Ejemplo de for in y for of:

```js
let animales = ['leon','perro','gato'];//esto es un array

for (animal in animales){//aca animal es igual a la pocision 0 del array
    document.write(animal + '<br>');//se ejecuta animal (0) y al ser un loop, se van ejecutando en cadena las demas palabras
}

document.write('<br>');//se ejecuta un espacio en linea

for (animal of animales){//aca pasa lo mismo, pero en vez de mostrarse el numero de la fila, se muestra el dato que contiene cada valor(['leon','perro','gato'])
    document.write(animal + '<br>');//se ejecuta diciendo cada valor en pantalla
}
```
`for in: devuelve indice`

`for of: devuelve valor`

---

- Ejemplo for in/of con Label:

```js
let array1 = ['juan','carlos','maria'];
let array2 = ['fabri','nashe',array1,'jorgelin'];

forPrimero: //esto es un label y separa el primer bucle del segundo a la hora de hacer un break o un continue
for (let array in array2) { //en este bucle se ejecuta el array2 hasta la posicion 2 ya que luego empieza el array1)
    if (array == 2) {//se usa un if para decir en que posicion termina el bucle


        for (let array of array1) { //en este bucle se ejecuta el array1
            document.write(array + '<br>');//se imprime la variable que se coloco en el for dejando lineas de espacio 
        }


    } else {
        document.write(array2[array] + '<br>'); //este else se imprime de todas maneras si los demas fallan, esta dentro del primer for
    }
}
```
---
# Funciones (Parte 1)
---
>Una función en JavaScript es similar a un procedimiento — un conjunto de instrucciones que realiza una tarea o calcula un valor, pero para que un procedimiento califique como función, debe tomar alguna entrada y devolver una salida donde hay alguna relación obvia entre la entrada y la salida.

- Como se declara una function:


```js
function saludar() {//asi se declara una function
}

saludar()//aca se ejecuta la function
```

- de que formas se usan?

```js
function saludar() {
    alert('Hello')
    return "Goodbye"//esto se retorna y se finaliza la function, lo que sigue despues de esto no sale en la function

}

let saludos = saludar()// esto se puede usar asi, o como en el primer ejemplo
```
---
- Funciones con parametros:

```js
function suma(num1,num2){//lo que esta entre parentesis es un parametro, y sirve para definir las variables y diferenciarlas de las demas funciones
    let resultado = num1 + num2;
    document.write(resultado);//esto se ejecuta en este bloque
}

suma(50,50)
```

- ejemplo con return:

```js
function suma(num1,num2){
    let resultado = num1 + num2;
    return resultado
}

let resultado = suma(50,50);//aca estamos diciendo que la variable resultado contiene el valor suma(), por lo tanto lo que este adentro de los parentesis es el valor de cada variable.
document.write(resultado); //ahora se ejecuta resultado y no suma(), ya que es lo mismo pero asignado a la variable resultado.
```

```js
function saludar(nombre){
    let frase = `Hola ${nombre}, como estas? `;
    document.write(frase)
}

saludar('Anonimo');
```
---

- Funciones flechas:

```js
const saludar = (nombre)=>{//esto es una function flecha, esta mucho mas optimizada y no requiere tantos recursos
    document.write(`hola ${nombre}, como estas?`);
}
saludar('pepe')
```
---
# Crear soluciones (Parte 2)
---
### PROBLEMA 1

- mini sistema de validacion en un boliche: se tiene que saber si son mayores de edad y quien entra gratis despues de las 2AM y quien tiene que pagar la entrada.

`Solucion:`
```js
let free = false;

const validarCliente = (time)=>{// funcion que explica la hora exacta de las personas que ingresan
    let edad = prompt("Cuantos años tenes master?");// variable con prompt, preguntando la edad de las personas
    if (edad > 17) {// se valida si sos mayor a (17)
        if (time >= 2 && time < 7 && !free) {//se valida si time es mayor o igual a 2AM y time es menor a 7AM y free que se asigno como false, pasa a ser true 
            alert("Podes pasar GRATIS porque sos la primer persona despues de las 2 AM");// si todo lo anterior se cumple, se confirma este alert.
            free = true;//esto se usa para que funcione solo una vez lo de entrar gratis
        } else{// si no se valida lo anterior, vas a tener que pagar la entrada
            alert(`Son las ${time}:00hs y podes pasar, pero tenes que pagar 500$`)
        }
    } else {// y si tu edad es menor a 18, directamente no pasas
        alert("sos menor capo, tomate el buque")
    }
}
// se ponen muchas funciones para decir los horarios de entrada de cada persona
validarCliente(23);
validarCliente(24);
validarCliente(0.2);
validarCliente(0.6);
validarCliente(1);
validarCliente(2);
validarCliente(2.4);
validarCliente(3);
```
---
### PROBLEMA 2

- mini sistema de asistencias e inasistensias en un colegio, se tiene que saber la cantidad de alumnos que hay, la cantidad de veces que asistieron a clases en el mes y sacar el 10% de inasistencias en todo caso de reprobar.

```js
let cantidad = prompt('cuantos alumnos son?');
let alumnosTotales = [];

for (i = 0; i < cantidad; i++) {
    alumnosTotales[i] = [prompt("nombre del alumno " + (i+1)),0];//esto es un array dentro de otro array
}

const tomarAsistencia = (nombre,p)=>{//funcion que nos pide el nombre y la posicion en la lista
    let presencia = prompt(nombre);//aca le vamos a decir si la persona esta presente, poniendo (A o P)
    if (presencia == 'p' || presencia == 'P') {//si presencia es igual p o P se suma +1
        alumnosTotales[p][1]++;//aca estamos seleccionando un elemento del array que esta dentro de otro array
    }
}

for (i = 0; i < 30; i++){//esto es para ejecutar 30 veces el bucle, por los 30 dias del mes aprox
    for (alumno in alumnosTotales) {//esta recorriendo el 2do array, con el nombre alumno(indice)
        tomarAsistencia(alumnosTotales[alumno][0],alumno);//el primer alumno tiene el nombre y ademas se le agrega el alumno que determina la pocision.
    }
}

for (alumno in alumnosTotales){
    let resultado = `${alumnosTotales[alumno][0]}:<br>
    ________Presentes: <b>${alumnosTotales[alumno][1]} </b> <br>
    ________Ausencias: <b>${30 - parseInt(alumnosTotales[alumno][1])}</b>`;
    if (30 - alumnosTotales[alumno][1] > 18) {
        resultado+= "<b style='color:red'> REPROBADO POR INASISTENCIA</b><br><br>";
    } else {
        resultado+= "<br><br>";
    }
    document.write(resultado);
}
```
---

### PROBLEMA 3

- Calculadora basica de suma,resta,division y multiplicacion.

```js
const suma = (num1,num2)=>{
    return parseInt(num1) + parseInt(num2);
}
const restar = (num1,num2)=>{
    return parseInt(num1) - parseInt(num2);
}
const dividir = (num1,num2)=>{
    return parseInt(num1) / parseInt(num2);
}
const multiplicar = (num1,num2)=>{
    return parseInt(num1) * parseInt(num2);
}

alert('Que operacion queres realizar?');
let operacion = prompt('1: suma, 2: resta, 3: dividir, 4: multiplicación');

if (operacion == 1) {
    let numero1 = prompt('primer numero para sumar');
    let numero2 = prompt('segundo numero para sumar');
    let resultado = suma(numero1,numero2);
    alert(`tu resultado es ${resultado}`);
}
else if (operacion == 2) {
    let numero1 = prompt('primer numero para restar');
    let numero2 = prompt('segundo numero para restar');
    let resultado = restar(numero1,numero2);
    alert(`tu resultado es ${resultado}`);
}
else if (operacion == 3) {
    let numero1 = prompt('primer numero para dividir');
    let numero2 = prompt('segundo numero para dividir');
    let resultado = dividir(numero1,numero2);
    alert(`tu resultado es ${resultado}`);
}
else if (operacion == 4) {
    let numero1 = prompt('primer numero para multiplicar');
    let numero2 = prompt('segundo numero para multiplicar');
    let resultado = multiplicar(numero1,numero2);
    alert(`tu resultado es ${resultado}`);
}
else {
    alert('No se ha encontrado la operacion.')
}
```
---
# Conceptos basicos de POO
---

- ¿Que es POO? Es un paradigma de la programación en el que se crean objetos para la manipulacón de datos y donde, por lo general, cada objeto ofrece una funcionalidad especial. La idea básica de la POO es que usamos objetos para modelar cosas del mundo real. POO nos ayuda a la reutilización del código.

`ejemplo basico:`

```js
class animal {//esto es una clase
    constructor(especie,edad,color){//esto es el constructor de la clase
        this.especie = especie;//se usa el (this.) para asignar cada valor  del constructor
        this.edad = edad;
        this.color = color;
        this.info = `Soy ${this.especie}, tengo ${this.edad} años y soy de color ${this.color}`;
    }
    verInfo(){//esto es un metodo y funciona solo para este bloque
        document.write(this.info + "<br>");
    }
}

const perro = new animal('perro',4,'marron');//se asigna const para asignar el orden del objeto (especie,edad,color)
const cabra = new animal('cabra',3,'blanca');//se usa (new) seguido del nombre de la clase, para referirse al objeto
const pajaro = new animal('pajaro',2,'verde');

perro.verInfo();//se ejecuta el nombre de la variable const, seguido del metodo asignado en la clase.
cabra.verInfo();
pajaro.verInfo();
```
---
# Caracteristicas de la POO
---

- Distinción entre clase y objeto. La distinción entre clase y objeto es una de las claves de este tipo de programación que la hace única.
- Reutiliza el código y evita su duplicación.
- Encapsula la información.
- Polimorfismo.

```js
class Animal {
    constructor(especie,edad,color){
        this.especie = especie;
        this.edad = edad;
        this.color = color;
        this.info = `soy un ${this.especie}, tengo ${this.edad} años y soy de color ${this.color}`;
    }
    verInfo(){
        document.write(this.info + "<br>");
    }
}

class Perro extends Animal {//de esta forma le estamos diciendo que herede las propiedades anteriores
    constructor(especie,edad,color,raza){//aca le decimos que tipo de datos tiene el objeto
        super(especie,edad,color);//aca definimos que queremos que herede de la clase anterior
        this.raza = raza;//definimos raza con this.
    }
    ladrar(){//hacemos un metodo
        alert('Waww waw!!');
    }
}



const perro = new Perro('perro',3,'beige','bulldog');
const gato = new Animal('gato',5,'negro');
const cangrejo = new Animal('cangrejo',2,'rojo');

perro.ladrar();
gato.verInfo();
cangrejo.verInfo();
```

---

### Metodo Static

- Para usar el metodo STATIC no hace falta crear la definicion para ser ejecutado, solamente poniendo el nombre de la clase y la accion que queremos asignar, ya funcionaria.

```js
class Animal {
    constructor(especie,edad,color){
        this.especie = especie;
        this.edad = edad;
        this.color = color;
        this.info = `soy un ${this.especie}, tengo ${this.edad} años y soy de color ${this.color}`;
    }
    verInfo(){
        document.write(this.info + "<br>");
    }
}

class Perro extends Animal {
    constructor(especie,edad,color,raza){
        super(especie,edad,color);
        this.raza = raza;
    }
    static ladrar(){// creamos el metodo static con la accion que queremos ejecutar
        alert('Waw Waw!')
    }
}

// NO HAY un const que defina a perro, por lo tanto con static se ejecuta de igual manera

Perro.ladrar(); // aca se usa el nombre de la clase y con el static ya funciona
```

### Metodos Setters & Getters

- Los metodos Getters (Get) sirven para obtener un valor y los Setters (Set) sirven para definir un valor


```js
class Animal {
    constructor(especie,edad,color){
        this.especie = especie;
        this.edad = edad;
        this.color = color;
        this.info = `soy un ${this.especie}, tengo ${this.edad} años y soy de color ${this.color}`;
    }
    verInfo(){
        document.write(this.info + "<br>");
    }
}

class Perro extends Animal {
    constructor(especie,edad,color,raza){
        super(especie,edad,color);
        this.raza = null; // colacamos null para poder modificarlo con los metodos set y get.
    }
    set setRaza(newName){// asignamos el metodo set y definimos setRaza con el parametro newName, para guiarnos con ese nombre en la modificacion
        this.raza = newName;// lo asignamos en el this.raza para modificarlo
    }
    get getRaza(){
        return this.raza;// returnamos el valor de this.raza
    }
}

const perro = new Perro("Perro",4,"Marron","Marron");

perro.setRaza = "Doberman";// modificamos el valor de "newName"
document.write(perro.getRaza);// aca obtenemos el valor que nos dio getRaza en la pantalla
```
---
# Crear soluciones (Parte 3)
---

- crear las funciones y caracteristicas basicas de los celulares.
  - hacer 3 celulares
  - diferenciar si es de alta gama o no
  - administrar las aplicaciones para descargar, seleccionar 2 apps de las 7 destacadas.

> Problema 1

```js
class Celular{//creacion de clase
    constructor(color,peso,rdp,rdc,ram){//definiendo las caracteristicas y asignando los valores
        this.color = color;
        this.peso = peso;
        this.resolucionDePantalla = rdp;
        this.resolucionDeCamara = rdc;
        this.MemoriaRam = ram;
        this.encendido = false;
    }
    botonDeEncendido(){
        if(this.encendido == false){
            alert("Celular prendido");
            this.encendido = true;
        } else {
            alert("Celular apagado");
            this.encendido = false;
        }
    }
    reiniciar(){
        if(this.encendido == true){
            alert("El telefono se esta reiniciando")
        } else {
            alert("El telefono esta apagado");
        }
    }
    tomarFoto(){
        alert(`Capturando foto con una resolucion de: ${this.resolucionDeCamara}`);
    }
    grabarVideo(){
        alert(`Grabando video con una resolucion de: ${this.resolucionDeCamara}`);
    }
    mobileInfo(){
        return `Color: <b>${this.color}</b><br>
                Peso: <b>${this.peso}</b><br>
                Tamaño: <b>${this.resolucionDePantalla}</b><br>
                Resolucion de Video: <b>${this.resolucionDeCamara}</b><br>
                Memoria ram: <b>${this.MemoriaRam}</b><br>`
    }
}

const celular1 = new Celular("Rojo","130g","5'","Full HD","2GB");//definiendo los valores de cada atributo
const celular2 = new Celular("Verde","120g","4.6'","HD","1GB");//definiendo los valores de cada atributo
const celular3 = new Celular("Azul","105g","7'","4k","4GB");//definiendo los valores de cada atributo




celular1.botonDeEncendido();//ejecutando las acciones del celular
celular1.tomarFoto();
celular1.grabarVideo();
celular1.reiniciar();
celular1.botonDeEncendido();

document.write(`
    ${celular1.mobileInfo()} <br>
    ${celular2.mobileInfo()} <br>
    ${celular3.mobileInfo()}`);
```
---

>Problema 2

```js
class Celular{//creacion de clase
    constructor(color,peso,rdp,rdc,ram){//definiendo las caracteristicas y asignando los valores
        this.color = color;
        this.peso = peso;
        this.resolucionDePantalla = rdp;
        this.resolucionDeCamara = rdc;
        this.MemoriaRam = ram;
        this.encendido = false;
    }
    botonDeEncendido(){
        if(this.encendido == false){
            alert("Celular prendido");
            this.encendido = true;
        } else {
            alert("Celular apagado");
            this.encendido = false;
        }
    }
    reiniciar(){
        if(this.encendido == true){
            alert("El telefono se esta reiniciando");
        } else {
            alert("El telefono esta apagado");
        }
    }
    tomarFoto(){
        alert(`Capturando foto con una resolucion de: ${this.resolucionDeCamara}`);
    }
    grabarVideo(){
        alert(`Grabando video con una resolucion de: ${this.resolucionDeCamara}`);
    }
    mobileInfo(){
        return `Color: <b>${this.color}</b><br>
                Peso: <b>${this.peso}</b><br>
                Tamaño: <b>${this.resolucionDePantalla}</b><br>
                Resolucion de Video: <b>${this.resolucionDeCamara}</b><br>
                Memoria ram: <b>${this.MemoriaRam}</b><br>`;
    }
}

class celularAltaGama extends Celular {
    constructor(color,peso,rdp,rdc,ram,rdce){
        super(color,peso,rdp,rdc,ram);
        this.resolucionDeCamaraExtra = rdce;
    }
    grabarVideoLento(){
        alert("Estas grabando en camara lenta");
    }
    reconocimientoFacial(){
        alert("Vamos a iniciar un reconocimiento facial");
    }
    infoAltaGama(){
        return this.mobileInfo() + `Resolucion de camara extra: ${this.resolucionDeCamaraExtra}`;
    }
}

const celular1 = new celularAltaGama("Rojo","130g","5.2","4k","3GB","Full HD");
const celular2 = new celularAltaGama("Negro","125g","6","4k","4GB","HD");

document.write(`
        ${celular1.infoAltaGama()} <br><br>
        ${celular2.infoAltaGama()} <br>`)
```

> Problema 3

```js
class App {
    constructor(descargas,puntuacion,peso){
        this.descargas = descargas;
        this.puntuacion = puntuacion;
        this.peso = peso;
        this.iniciada = false;
        this.instalada = false;
    }
    abrir(){
        if(this.iniciada == false && this.instalada == true){
            this.iniciada = true;
            alert("Aplicacion Encendida");
        }
    }
    cerrada(){
        if(this.iniciada == true && this.instalada == true){
            this.iniciada = false;
            alert("Aplicacion Cerrada");
        }
    }
    instalar(){
        if(this.instalada == false){
            this.instalada = true;
            alert("Aplicacion Instalada correctamente");
        }
    }
    desinstalar(){
        if(this.instalada == true){
            this.instalada = false;
            alert("Aplicacion Desinstalada");
        }
    }
    appInfo(){
        return `
        Descargas: <b>${this.descargas}</b><br>
        Puntuacion: <b>${this.puntuacion}</b><br>
        Peso: <b>${this.peso}</b><br>`;
    }
}

// app.instalar();      // funciones basicas de las aplicaciones
// app.abrir();
// app.cerrada();
// app.desinstalar();

const app = new App("1M","3.7 Estrellas","240Mb"); // caracteristicas de las aplicaciones
const app2 = new App("50.000","2.8 Estrellas","540Mb");
const app3 = new App("750.000","4.5 Estrellas","900Mb");
const app4 = new App("20.000","5 Estrellas","320Mb");
const app5 = new App("10.000","1.8 Estrellas","650Mb");
const app6 = new App("800","2.3 Estrellas","52Mb");
const app7 = new App("5.650","4.1 Estrellas","92Mb");

document.write(`
    ${app.appInfo()}<br>
    ${app2.appInfo()}<br>
    ${app3.appInfo()}<br>
    ${app4.appInfo()}<br>
    ${app5.appInfo()}<br>
    ${app6.appInfo()}<br>
    ${app7.appInfo()}<br>`); // descripcion en pantalla de las aplicaciones
```
---
