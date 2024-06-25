# Desafíos del curso de lógica de programación

¡Hola a todos! Actualmente, soy estudiante del programa de capacitación y empleabilidad Oracle Next Education (ONE) el grupo número 7. Como primer curso se encuentra la lógica de programación, si bien tengo conocimientos previos, ya que soy estudiante de Ing. de sistemas, no está de más repasar este tema tan importante para la creación de algoritmos. Quiero compartir con ustedes los desafíos de la primera clase con JavaScript.


1. Muestra una alerta con el mensaje "¡Bienvenida y bienvenido a nuestro sitio web!".
```javascript
alert('¡Bienvenida y bienvenido a nuestro sitio web!');
```

2. Declara una variable llamada nombre y asígnale el valor "Luna".
```javascript
let nombre = "Luna";
```

3. Crea una variable llamada edad y asígnale el valor 25.
```javascript
let edad = 25;
```

4. Establece una variable numeroDeVentas y asígnale el valor 50.
```javascript
let numeroDeVentas = 50;
```

5. Establece una variable saldoDisponible y asígnale el valor 1000.
```javascript
let saldoDisponible = 1000;
```

6. Muestra una alerta con el texto "¡Error! Completa todos los campos".
```javascript
alert('¡Error! Completa todos los campos');
```

7. Declara una variable llamada mensajeDeError y asígnale el valor "¡Error! Completa todos los campos". Ahora muestra una alerta con el valor de la variable mensajeDeError.
```javascript
let mensajeDeError = '¡Error! Completa todos los campos';

alert(mensajeDeError);
```

8. Utiliza un prompt para preguntar el nombre del usuario y almacénalo en la variable nombre .
```javascript
let nombre = prompt('Ingrese su nombre');
```

9. Pide al usuario que ingrese su edad usando un prompt y almacénala en la variable edad.
```javascript
let edad = prompt('Ingrese su edad');
```

10. Ahora, si la edad es mayor o igual a 18, muestra una alerta con el mensaje "¡Puedes obtener tu licencia de conducir!".
```javascript
let edad = prompt('Ingrese su edad');
if (edad >= 18) {
    alert('¡Puede obtener su licencia de conducir!');
}
```


# Desafíos del curso de lógica de programación #2 


1. Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
```javascript
let diaSemana = prompt('¿Qué día de la semana es?');

if (diaSemana === 'Sábado' || diaSemana === 'Domingo') {
    alert('¡Buen fin de semana!');
} else {
    alert('¡Buena semana!');
}
```
2. Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.
```javascript
let numero = prompt('Escribe un número:');

if (numero > 0) {
    alert('El número es positivo');
} else if (numero < 0) {
    alert('El número es negativo');
} else {
    alert('El número es cero');
}
```
3. Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".
```javascript
let puntuacionAc = 95;

if (puntuacionAc >= 100) {
    console.log('¡Felicidades, has ganado!');
} else {
    console.log('Intentalo nuevamente para ganar.');
}
```
4. Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.
```javascript
let saldo = 200.000; 

alert(`Tu saldo es de ${saldo}.`);
```
5. Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.
```javascript
let nombre = prompt('Ingresa tu nombre:');

alert(`¡Bienvenido, ${nombre}!`);
```


# Desafíos del curso de lógica de programación #3 


1. Crea un contador que comience en 1 y vaya hasta 10 usando un bucle 'while'. Muestra cada número.
```javascript
let contador = 1;

while (contador <= 10) {
   console.log(contador);
   contador++;
}
```
2. Crea un contador que comience en 10 y vaya hasta 0 usando un bucle 'while'. Muestra cada número.
```javascript
let contador = 10;

while (contador >= 0) {
   console.log(contador);
   contador--;
}
```
3. Crea un programa de cuenta progresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.
```javascript
let numero = prompt("Ingresa un número:");

while (numero >= 0) {
   console.log(numero);
   numero--;
}
```
4. Crea un programa de cuenta progresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.
```javascript
let numero = prompt("Ingresa un número:");;
let contador = 0;

while (contador <= numero) {
   console.log(contador);
   contador++
}
```


# Desafíos del curso de lógica de programación #4

1. Crea un programa que utilice console.log para mostrar un mensaje de bienvenida.
```javascript
console.log('¡Bienvenido a mi web!');
```
2. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza console.log para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador.
```javascript
nombre = 'Monica Plata';

console.log(`¡Hola, ${nombre}!`);
```
3. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza alert para mostrar el mensaje "¡Hola, [tu nombre]!".
 ```javascript
 nombre = 'Monica Plata';

 alert(`¡Hola, ${nombre}!`);
```
4. Utiliza prompt y haz la siguiente pregunta: ¿Cuál es el lenguaje de programación que más te gusta?. Luego, almacena la respuesta en una variable y muestra la respuesta en la consola del navegador.
```javascript
lenguajeP = prompt('¿Cuál es el lenguaje de programación que más te gusta?');

console.log(lenguajeP);
```
5. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la suma de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
let valor1 = 6;
let valor2 = 13;
let resultado = valor1 + valor2;

console.log(`La suma de ${valor1} y ${valor2} es igual a ${resultado}.`);
```   
6. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la resta de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
let valor1 = 9;
let valor2 = 28;
let resultado = valor1 - valor2;

console.log(`La diferencia entre ${valor1} y ${valor2} es igual a ${resultado}.`);
```
7. Pide al usuario que ingrese su edad con prompt. Con base en la edad ingresada, utiliza un if para verificar si la persona es mayor o menor de edad y muestra un mensaje apropiado en la consola.
```javascript
edad = prompt('Ingresa tu edad:');

if(edad > 17){
  console.log('Eres mayor de edad.');
}else{
  console.log('Eres menor de edad.');
}
```
8. Crea una variable "numero" y solicita un valor con prompt. Luego, verifica si es positivo, negativo o cero utilizando un if-else y muestra el mensaje correspondiente.
```javascript
numero = parseFloat(prompt("Ingresa un número:"));

if(numero > 0){
  console.log("El número es positivo.");
}else if(numero < 0){
  console.log("El número es negativo.");
}else{
  console.log("El número es cero.");
}
```
9. Utiliza un bucle while para mostrar los números del 1 al 10 en la consola.
```javascript
numero = 1;

while (numero <= 10){
  console.log(numero);
  numero++;
}
```
10. Crea una variable "nota" y asígnale un valor numérico. Utiliza un if-else para determinar si la nota es mayor o igual a 7 y muestra "Aprobado" o "Reprobado" en la consola.
 ```javascript
 nota = 8;

 if(nota >= 7){
   console.log("Aprobado");
 }else{
   console.log("Reprobado");
 }
 ```
11. Utiliza Math.random para generar cualquier número aleatorio y muestra ese número en la consola. 
```javascript
numeroAleatorio = Math.random();

console.log(numeroAleatorio);
```
12. Utiliza Math.random para generar un número entero entre 1 y 10 y muestra ese número en la consola.
 ```javascript
numeroIntAleatorio = parseInt(Math.random() * 10) + 1;

console.log(numeroIntAleatorio);
 ```
13. Utiliza Math.random para generar un número entero entre 1 y 1000 y muestra ese número en la consola.
 ```javascript
numeroIntAleatorio = parseInt(Math.random() * 1000) + 1;

console.log(numeroIntAleatorio);
 ```
