# Juego 3 Pac-Man

Este repositorio contiene el archivo pacman.py, que corresponde al videojuego Pac-Man desarrollado en Python.
El juego consiste en controlar a Pac-Man a través de un laberinto para comer todos los puntos blancos del tablero mientras se evita el contacto 
con cuatro fantasmas que patrullan el mapa.

##Modificaciones realizadas

###1. Inteligencia Artificial de los fantasmas

Se implementó un sistema de navegación inteligente para que cada fantasma tenga un comportamiento único y un color representativo para su 
identificación:

Blinky (Rojo): Persigue de forma directa la posición exacta de Pac-Man.
Pinky (Rosa): Trata de anticipar el movimiento de Pac-Man para cerrarle el paso y emboscarlo.
Inky (Cian): Realiza un seguimiento constante buscando flanquear al jugador.
Clyde (Naranja): Mantiene una conducta errática; persigue a Pac-Man si está lejos, pero se retira si se acerca demasiado.

###2. Rediseño del tablero 

Se modificó la matriz de baldosas (tiles) abriendo nuevas rutas y pasillos en el mapa. Esto permite una mayor fluidez de movimiento, ofreciendo 
más alternativas para esquivar a los fantasmas y eliminando callejones sin salida.

###3. Ajustes de velocidad y desplazamiento

Se incrementó la velocidad base del Pac-Man y de los fantasmas para aumentar la dificultad y hacer la partida más dinámica. Asimismo, se 
actualizaron los vectores de dirección de los fantasmas a pasos de 10 unidades para coordinar su desplazamiento con los nuevos caminos.

###4. Limpieza y optimización del código

Se depuró la estructura del archivo eliminando líneas redundantes, espacios en blanco y corrigiendo el formato de la matriz del escenario, 
logrando un código más limpio y fácil de mantener.
