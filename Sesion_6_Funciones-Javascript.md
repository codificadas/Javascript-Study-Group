Funciones de Javascript
===

Javascript cuenta con funciones predefinidas que podemos en cualquier ocasión en que queramos obtener o enviar información al usuario.  
Algunas de las funciones las veremos a continuación:  

*alert()*
--

Sirve para enviar mensajes al usuario en una pequeña ventana emergente.  
El mensaje se envía como un parámetro a la función con un texto entre paréntesis. El valor que se envía aquí puede ser cualquier valor o cadena.  

Ejemplo:
--
<code>
alert("Alert! Alert! Last call to board Train #4!");  
</code>

*confirm()*
--

Sirve para preguntar al usuario su consentimiento para continuar una acción.  

Ejemplo:
--
<code>
confirm("Dude. Are you sure you wanna ride #8? Just saying.");  
</code>

*prompt()*
--

Envía un mensaje al usuario y muestra un campo de texto para que el usuario inserte algún valor.  

Ejemplo:
--

<code>
prompt("What soul hath allowed the canines to exit?");  
</code>


Cómo ya se mencionó, esta función permite que el usuario ingrese algún valor y podamos recibirlo en una variable.   Ejemplo:    
<code>
	var username = prompt("Yo passenger! What's your name?");  
</code>

*Operador typeof*
--

El operador typeof permite identificar el tipo de datos que se encuentra en una variable o expresión:  

Ejemplo:
<code>
	typeof true  
</code>
.. regresaría "boolean" como el tipo de valor de la expresión

<code>
	typeof "That's not a valid entry!"  
</code>
.. regresaría "string"  

<code>
	typeof "42"  
</code>
.. regresaría "number"  

<code>
	typeof null  
</code>
.. regresaría "object"


Funciones
==

Las funciones son un conjunto de instrucciones que se agrupan para realizar una tarea concreta y se pueden reutilizar fácilmente. Esto es muy útil, por ejemplo, cuando durante el desarrollo de una aplicación necesitamos ejecutar varias veces las mismas instrucciones. Por ello en lugar de que escribamos las mismas instrucciones muchas veces, lo que se hace es poner dichas instrucciones dentro de una función, y de esa manera sólo llamar la función cuando necesitemos que se ejecuten esas instrucciones.

Sintaxis básica de una función
--
<code>
function nombreDeLaFuncion](parametro1, parametro2){  
	*Instrucciones*
	return valor;
}  
</code>

Ejemplo
--
La siguiente función recibe dos numéros com parámetros, obtiene el cubo de cada uno de ellos y los suma; al final, regresa el resultado de la suma.  
<code>
function sumOfCubes(a, b){  
	var aCubed = a*a*a;  
	var bCubed = b*b*b;  
	var sum = aCubed + bCubed;  
	return sum;  
}  
</code>
*NOTA:* Ahora puedes realizar los ejercicios de las diapositivas corespondientes a esta sesión! :).

Alcance global y alcance local de las variables.  
--

- Dentro de las funciones, el alcance las variables es local; es decir, las variables que se declaren ahí sólo pueden ser usadas dentro de la misma función.  

- Fuera de las funciones, el alcance las variables es global; es decir, las variables que se declaren en el programa principal pueden ser usadas en cualquier parte del mismo, incluso dentro de cualquie función.

*Ejemplo:*   
<code>
var x = 6;  
function add(a, b){  
	var x = a+b;  
	return x;  
}  
</code>
En este caso la variable <code>x</code> que se declaró dentro de la función es diferente a la que se declaró afuera.  

<code>
var x = 6;  
function add(a, b){  
	x = a+b;  
	return x;  
}  
</code>
En este caso, la variable <code>x</code> que se usa dentro de la función es la misma que está declarada fuera de ella. 

Diapositivas
-- 
[Sesión 6](https://www.haikudeck.com/javascript-functions-uncategorized-presentation-oMirgAK9Xj)