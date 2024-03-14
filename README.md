# Gabriel Miguel Cabrera Samano 
no.control: 20491199

## 1. Que hace document.querySelector(".display"); ?
- el comando permite regresar al primer elemento con el que el documento este ligado al selector en especifico, en este caso el elemento es la clase ".display".
- Dentro del programa este valor lo almacenamos en una variable constante, de manera que cualquier valor ingresado en el display se identifique en la evaluacion del documento.
## 2. Que hace const buttons = document.querySelectorAll("button"); ?
- al igual que con el comando anterior, permite retornar a los elementos que el documento determina al selector en especifico.
- querySelector cuenta con diferentes variantes dependiendo del grupo que estamos relacionando, el caso anterior era a un unico selector (aunque tambien puede presentarse un grupo).
- sin embargo, querySelectorAll() nos ayuda a retornar a todos los elementos que conforman el tipo de selector, en este caso todas aquellas que se involucren con el comando button.
## 3. Que hace buttonText = button.textContent; ?
- nos permite almacenar el contenido del texto por parte de las etiquetas button y almacenarlo en una variable.
## Que hace y como funciona buttons.forEach((button) => { ...} ?
- La expresión buttons.forEach((button) => { ... }) se define como un ciclo que evalua una coleccion de elementos mediante un arreglo.
- esta aplicado es por parte del foreach y se aplica a un array de botones.
- buttons es el arreglo que contiene los elementos del boton representando la etiqueta en el documento.
- (button) => { ... } nos indica que mediante el parámetro button representara cada elemento del array buttons. el comportamiento que se ejecutará en cada iteración del bucle forEach para cada elemento del array es por parte de su condicion =>.
## Que hace y como funciona button.addEventListener("click", () => { } )
- La expresión button.addEventListener("click", () => { }) realiza un "escuchador de eventos" para el acceso de los botones al momento de interactuar con ellos mediante un click:
- .addEventListener considera dos argumentos:
- "click": Este es el tipo de evento al que se está escuchando. En este caso, estamos escuchando el evento de clic del ratón en el botón.
- () => { }: Esta es una función flecha que define el comportamiento que se ejecutará cuando ocurra el evento especificado (en este caso, el evento de clic).
