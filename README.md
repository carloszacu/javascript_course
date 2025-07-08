# javascript_course

Javascript course with that Argentinian dude (<https://perficient.udemy.com/course/javascript-total/learn/lecture/34226688#content>)
mis instrucciones

## NOTAS VARIAS DEL CURSO JavaScript

las variables en Javascript como en cualquier lenguaje, son contenedores para ingresar valores variables

las variables en Javascript se usan de la siguiente manera.

```javascript
let nombreVariable = "hola Mundo";
```

y se invocan con el nombre de la variable, sobra decir que los nombres de las veriables deben ser únicos y que pueden ser declaradas en cualquier punto del código.

las variables pueden contener Numeros enteros (int) o numeros decimales (float) ambos pueden ser positivos o negativos, nota importante: los números no van entre comillas, si el valor númerico se escribe entre comillas el sistema los toma como texto por lo que no se podrá hacer operaciones con ellos.

```javascript
let Number = 700;
let notANumber = "700";
```

Como ya sabemos también podemos usar texto ubicando entre comillas el valor, o también podemos usar las variables tipo boolean (truo or false)

```javascript
let tengoBarba = true;
let tengoPelo = false;
```

También podemos usar array's que son cadenas de datos y se usan en corchetes separados por comas

```javascript
let arrayText = ["Juan", "Carlos", "Pedro"];
let arraynumbers = [5,2,8];
```

cuando queremos acceder a la información de un arreglo en una variable lo que hacemos es que entre corchetes indicamos la posición que necesitamos, recordemos que las posiciones en los arreglos comienzan desde el cero, con esto en mente la segunda posición de un arreglo sería la 1:

```javascript
let arrayText = ["Juan", "Carlos", "Pedro"];
arrayText[1];
```

En el ejemplo anterior, el sistema mostraría el valor "Carlos".

Las variables también pueden contener objetos de la siguiente manera:

```javascript
let myDog = {race = 'Labrador'
             name = 'Jack'
             age = 12}
```

Para usar comillas dentro de una cadena de texto en una variable tipo string debemos encerrar la cadena de texto entre Backticks (acento fuerte - Alt + 96) así:

```javascript
let misBellos = `la verdad barba tengo pero "Pelo" como tal 'no'` ;
```

En HTML el podemos asignarle el valor que queramos de la siguiente manera:

```javascript
let texto = document.getElementById("inputTexto").value;
```

En esta función estamos buscando un elemento HTML a traves de su id (que en este caso el id es inputTexto) y le indicamos que lo que queremos de ese elemento es el valor (value) no el elemento como tal.

En Javascript podemos usar una función de tiempo que nos permite contar el tiempo antes de ejecutar otra función y se coloca de esta manera:

```js
function startTime() {
            let time = document.getElementById("timeInput").value;
            setTimeout(timeOut, 1000 * time);
        }
```

Donde Timeout es la función que se ejecuta después de cumplirse el tiempo y el otro parámetro es la cantidad de tiempo en milisegundos, en este parámetro se pueden usar tanto variables como operaciones matemáticas.

Ahora para usar Audio en las páginas podemos usar las siguientes etiquetas:

```html
<audio id="audioAlarm">
    <source src="audio/alarm.mp3" type="audio/mpeg">
    Sonido no Habilitado
</audio>
```

con el Source le indicamos la ubicación del archivo de audio, y el type es para indicarle que es un elemento multimedia.

si lo que queremos es usar un panel de control de reproducción de audio, podemos usar las mismas etiquetas audio, pero de la siguiente manera:

```html
<audio id="audioAlarm" controls>
    <source src="audio/alarm.mp3" type="audio/mpeg">
    Sonido no Habilitado
</audio>
```

De esta manera, agregando el atributo "controls" a la etiqueta "audio" podemos mostrar un reproductor de audio en la página web, este control puede después ser modificado a través de CSS como cualquier objeto HTML.

Para ello incluimos la etiqueta "Style" en el head del documento HTML y lo escribimos de la siguiente manera:

```html
<style>
        audio::-webkit-media-controls-panel {
            background-color: orange;
        }
    </style>
```

De esta manera configuramos que el objeto de control de multimeda tenga un fondo naranja.

Ahora para usar la fecha y hora del sistema debemos para usarla más claramente asignarle el valor a una variable y luego tomamos el valor directamente desde la variable

>[!NOTE]
>
>BLA BLA BLA BLA

>[!IMPORTANT]

>[!WARNING]

>[!CAUTION]

>[!TIP]
