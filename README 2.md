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