# Cohete_Llenguaje

## Proyecto de lenguaje de marcas.


Este proyecto ha sido creado por Achraf El Ouakili, del curso de desarrollo de aplicaciones multiplataformas del instituto IES Francesc de Borja Moll. 

La finalidad del proyecto es realizar la colocación previa de los elementos que van a ser usado en el juego que se realizara posteriormente llamado "Luna Lander".

La colocación de los elementos debía de corresponder a la que el alumno
[CRISTIAN FONTCUBERTA LÓPEZ](https://github.com/HighYitan/Proyecto-lunar-lander) presento como solución a la demanda del cliente.

Respecto a la colocación de elementos he hecho una serie de modificaciones para que el proyecto sea mas adecuado, estético y ocupe menos espacio.

### La primera modificación que he realizado es colocar los indicadores de:
* Velocidad
* Altura
* Combustible

En el lateral izquierdo para poder aprovechar mejor espacio. Y así tener mas distancia de caída para la nave. Los indicadores de "Velocidad" y el de "Altura" siguen funcionando de la misma manera que en el anterior diseño. Pero el indicador de combustible, he querido hacer una barra lateral que indique la capacidad. Así da al juego mas dinamismos. El estilo actual que le he dado a sido el siguiente.

Anterior

![Imagen anterior](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ1.PNG)

Actual

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ2.PNG)


### La segunda modificación que he realizado ha sido darle un diseño mas simple y minimalista a los iconos de :
* Pause
* Opciones
* Ayuda
* Start

Lo que he hecho es unir el botón de "Start" con el de "Pause", para ocupar así menos espacio.

Anterior

![Imagen anterior](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ3.PNG)

A los nuevos iconos les he intentado dar un color similar a el que tiene la nave. Para que mantengan así el estilo del juego. Además de que les he dado un efecto para que cuando clikes en ellos, sobre salgan y así sean mas llamativos.

Actual

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ4.PNG)

### Otras modificaciones

Otro cambio que he realizado para que el juego ocupe menos espacio es recortado el fondo y lo he dividido en elementos mas pequeños. 

El fondo original es el siguiente:

![Imagen anterior](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/Fondo%2Csineditar.jpg)

Para que ocupe menos he cogido una porción del fondo anterior, y ha hecho que se repita para obtener un resultado similar. 

El actual fondo es el siguiente:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/Fondo.jpg)

Además también he recortado la luna y la he separado del fondo. 

Luna actual:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/Luna.png)

### Diseño final

#### Al final el juego a quedado tal que así para los monitores:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ5.PNG)

El botón de "Pausa" y el de "Reset", tienen un link para recargar la pagina, ya que actualmente no he integrado el javascript.

El botón con el símbolo de interrogante ("?") te lleva a otra pagina web la cual tiene una breve definición de lo que hace el juego.

La pagina a la cual te redirige es la siguiente:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ7.PNG)

Y el ultimo botón que es el de ajustes que habría un menú con la posibilidad cambiar la dificultad o poner sonido al juego.

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ6.PNG)

Este menú de opciones actualmente esta desactivado mediante css, con la orden "display: none".

#### El diseño de los dispositivo móvil es el siguiente:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ8.PNG)

En el diseño para móvil he reunido todos los botones en uno y lo he llamado "Menu", el botón de "Menu" hará la función pause cuando le demos. Y además desplegara un menú con todas las opciones que podíamos tener en la versión de monitor. Aquí os dejo su estado desplegado:

![Imagen actual](https://github.com/ach74/Luna_Lander_Ach/blob/master/img/EsQ9.PNG)

En este caso tenemos el botón de reset y el de ayuda. Un inconveniente que he tenido ha sido no poder poner un link a dichos botones. Ya que los he declarado como "button", este pequeño inconveniente quedara solventado cuando pueda implementa el javascript.

Para finalizar esta presentación os dejo aquí el link de pertinente juego:

https://cdn.rawgit.com/ach74/Luna_Lander_Ach/bef87c6c/Cohete.html









