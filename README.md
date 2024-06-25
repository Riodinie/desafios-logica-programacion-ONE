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

