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


Alcance global y alcance local
--