Repaso
--

En la sesión anterior vimos un poco de la Historia de Javascript, además de algunas características de sintaxis del lenguaje, tales como: 
- La creación de cadenas y el uso de los caracteres de escape en las cadenas. 
- El uso de operadores aritméticos 
- Operadores lógicos y Boolenos

Variables
--
Javascript usa las variables para almacenar y manejar datos. 

Para declarar una variable utilizamos la palabra reservada **var** seguida del nombre que daremos a la variable, seguido por operador de asignacion **=** y finalmente el valor que se va a almacenar. La palabra **var** le indica al navegador que debe reservar un espacio para esa variable. 

Si en la consola ingresamos el nombre de nuestra variable y presionamos enter, veremos que nos imprime el valor que tiene almacenado.

Reglas para nombrar variables
--
- No debe tener espacios en blanco 
- No debe tener dígitos al inicio del nombre 
- Puede contener guion bajo y signo de pesos, pero no es una buena práctica. 
- El nombre ideal de una variable seria miVariable, iniciando con una minúscula y seguido por palabras que inician con mayúscula (camelcase) 

Cambiar el contenido de una variable
--
- Asignar el nuevo valor, ahora sin utilizar la palabra var, porque javascript ya sabe que existe esa variable previamente 
- Asignar un valor sobre la misma variable: 
<code>miVariable = miVariable +3</code> ó <code>miVariable += 3</code> 

<code>miVariable = miVariable * 2</code> ó <code>miVariable *=2</code> 

Concatenación de variables en cadenas
--
Incrementos y decrementos
- <code>miVariable++</code> 
- <code>miVariable--</code>

Ejercicios
--
- Almacenar cadenas en variables 

<code>var miGrupo = ‘Grupo de Javascript’</code>
- Concatenar variables de cadenas y caracteres de escape 

<code>miGrupo = ‘Grupo de Javascript:’</code>

<code>var bienvenida = ‘Todos son bienvenidos’</code> 

<code>miGrupo + ‘\n’ + bienvenida <code>

- Longitud de la cadena almacenada en la variable 
 
<code>var miNombre = ‘Ana Castro Martinez’</code> 

<code>miNombre.length</code> 

- Comparar longitud de cadenas 
 
<code>miNombre = ‘Ana …’</code> 

<code>miAmiga = ‘Selene …’</code> 

<code>miNombre.length > miAmiga.length</code>

- Encontrar caracteres dentro de cadenas (<code>charAt(index)</code>) 

Una cadena está compuesta por caracteres y cada uno de estos caracteres se enumeran empezando en 0, a esta enumeración se le llama index o posición.

<code>miNombre.charAt(2)</code> dará como resultado el caracter que se encuentra en la posición indicada(2).

Referencias
--
- [Sesión 2](https://www.haikudeck.com/p/ZXGSYb7xmx/javascript-study-group---2)
