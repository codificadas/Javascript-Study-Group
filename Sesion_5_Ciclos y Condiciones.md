Ciclos y Condiciones en Javascript
===

Las estructuras de control de flujo permiten que los programas no solamente sean un conjunto de instrucciones que se ejecutarán de una a una, sino que también puedan tomar decisiones de acuerdo a los valores que tienen las variables.


Dichas instrucciones son del tipo "si se cumple esta condición, haz esto; si no se cumple, haz esto otro" conocidas en programación como condiciones if - else. También existen instrucciones del tipo "repite esto mientras se cumple esta condición", conocidas como ciclos.

Ciclo WHILE
--

Sirve para ejecutar un conjunto de instrucciones un determinado número de veces, "mientras se cumple cierta condición":


**Ejemplo:**

<code>
	var number = 1;  
	while(number<5){  
		consola.log(number);  
		number++;  
	}  
</code>
- Escribe el código anterior en un archivo .js e incluýelo en el archivo HTML que ya se creó en sesiones anteriores, comprueba lo que se imprime en la consola de tu navegador preferido, ¿qué resultado ves?, ¿qué fué lo que hizo código?


**Ejercicio 1**:
- En un archivo "countdown.js" escribeun ciclo que imprima en la onsola todos los números del 10 al 1 en orden descendente.  
Pista: Comenzar con la siguiente instrucción:  
<code>var num = 10;</code>


Ciclo FOR
--

Sirve para ejecutar un conjunto de instrucciones un determinado número de veces, "mientras se cumple cierta condición", es también conocido como ciclo automático:


**Ejemplo**

<code>
	for(var number = 1; number<5; number++){  
		console.log(number);  
	}
</code>
- Escribe el código anterior en un archivo .js e incluýelo en el archivo HTML que ya se creó en sesiones anteriores, comprueba lo que se imprime en la consola de tu navegador preferido, ¿qué resultado ves?, ¿qué fué lo que hizo código?


**Ejercicio 2:**
- Escribe un ciclo FOR que imprima en la consola todos los números del 10 al 1 en orden descendente.

Reto 1!
--
En el Parque Nacional "Death Valley", un grupo de ambientalistas ha comenzado un proyecto con el que aunmentará la población de borregos cimarrones.
Cada mes, la población se multiplicará por 4!!.
Para estar al tanto de este crecimiento, los científicos quieren saber cuantos borregos habrá en el parque.
En un archivo "deathvalley.js", usa las tres variables existentes para construir un ciclo WHILE que imprima un mensaje cada mes durante un año como lo que se muestra a continuación:  
<code>
	Habrá 16 borregos después de 1 mes(es)  
	Habrá 64 borregos después de 2 mes(es)
</code>

Pista: Inicia con las siguientes variables:

<code>
	var numSheep = 4;  
	var monthNumber = 1;  
	var monthsToPrint = 12;
</code>


Condición if-else
--
Ésta es una de las estructuras más utilizadas y se emplea para tomar decisiones en función de los valores de nuestras variables:
Si la condición se cumple (es decir, si el resultado que se obtiene de la condición es true) se ejecutan las instrucciones dentro de <code>{...}</code>. Si la condición no se cumple (el resultado es false), el programa continúa y en caso de que exista un else, ejecuta lo que hay dentro de éste.


**Ejemplo**
<code>
	var value1 = 4;  
	var value2 = 9;  
	if(value1<value2){  
		console.log(value1 + " es menor que " + value2);  
	}else{  
		console.log(value1 + " es mayor o igual a " + value2);  
	}
</code>
- Escribe el código anterior en un archivo .js e incluýelo en el archivo HTML que ya se creó en sesiones anteriores. Antes de comprobar el resultado reflexiona lo siguiente: ¿qué resultado crees que se imprimirá en la consola?. Comprueba el resultado, puedes cambiar ahora los valores de tus variables value1 y value2, ¿cómo le harías que te muestre el otro mensaje?

**Ejercicio 3**
- Usa una condición para imprimir un mensaje en la consola, dependiendo del valor de la variable (parkIsOpen).

"Welcome to the Badlands National Park! Try to enjoy your stay."

ó

"Sorry, the Badlands are particularly bad today. We're closed!"

Pista: Empieza con la siguiente instrucción:  
<code>var parkIsOpen = true;</code>


Reflexión: cambia el valor de la variable para que compruebes que te muestre uno u otro mensaje!


Reto 2!
--
Con el código que creaste en el reto anterior los científicos pueden ver cuando la población de borregos de sale de control. Ellos han decidido que en cualquier mes en que la población sobrepase los 10000 borregos, enviarán a la mitad de ellos a otras regiones.
Dentro del ciclo agrega una condición que:
- Remueva la mitad de borregos si el número de estos es mayor que 10000.
- Imprima en la consola el número de borregos que fueron removidos. Ejemplo:
<code>Removiendo <number> borregos de la población.</code>

Pista: El código del primer reto debió quedar así:

<code>
	var numSheep = 4;  
	var monthsToPrint = 12;  
	for (var monthNumber = 1; monthNumber <= monthsToPrint; monthNumber++){  
		[insert your code here]
		numSheep *= 4;  
		console.log("Habrá " + numSheep + " después de " + monthNumber + " meses!");
	}
</code>


Diapositivas
--
- [Sesión 5](https://www.haikudeck.com/5---ciclos-y-condicionales-uncategorized-presentation-mHvykS9AwS#slide-16)
