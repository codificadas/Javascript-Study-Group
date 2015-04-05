Archivos JavaScript
====

En esta sesión vimos cómo incluir archivos con código JavaScript y con extensión .js dentro del html de nuestro sitio.

Práctica 1
==

1. Crear un directorio llamado root, y dentro de éste crear un archivo llamado index.html que contenga lo siguiente:

```
<html>
  <head>
  </head>
  <body>
    <h1>Welcome to JavaScript Express!</h1>
  </body>
</html>
```

2. Dentro de <head></head> incluir el tag <script></script>.
3. Crear un archivo llamado trains.js dentro del directorio root.
4. Incluir trains.js dentro de index.html

Práctica 2
==

1. Crear la siguiente estructura de directorios para nuestro sitio

```
  /root
    /site
      index.html
    /scripts
      trains.js
```

2. Agregar el siguiente código al archivo trains.js:

```
“Train #” + 1 + “ is running.”

“Train #” + 2 + “ is running.”

“Train #” + 3 + “ is running.”
```

3. Revisar la salida de la consola. ¿Sucedió algo?, ¿qué hace falta?
4. Después de analizar qué es lo que sucede, hacer las correcciones.
5. Recargar la página y ver si obtenemos el resultado esperado.

Práctica 3
==

1. Agregar el siguiente código a trains.js:

```
var totalTrains = 12;

var trainsOperational = 8;

console.log(“There are “ + trainsOperational + “ running trains.”);

console.log(totalTrains == trainsOperational);

```

2. Imprimir usando console.log, así:

```
console.log(“Train #” + 1 + “ is running.”);

console.log(“Train #” + 2 + “ is running.”);

console.log(“Train #” + 3 + “ is running.”);

```

3. Revisar la salida en la consola.
4. ¿Qué sucedería si tuviéramos 1000 trenes y queremos imprimir cada uno?
