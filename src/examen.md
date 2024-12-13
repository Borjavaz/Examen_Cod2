# ExamenCOD
## Primer ejercicio
### 
En este ejercicio vamos ha realizarun diagrama de flujo
![DiagramaDamas](file:///home/dam/Im%C3%A1genes/Damas1.jpg)
###
En el diagrama seguimos los suiguientes pasos:

1. **Declarar**
    - *Tenemos que declarar las variables y crear el tablero*
2. **Recorremos el tablero**
    - *Primero recorremoslas filas con unbucle for*
    - *Despues recorremos las columnas con otro bucle for*
3.  **Comprobamos si hay m,ás fichas blancas o negras**
    - *Sacamos por pantalla al ganador*
###
En este segundo ejercicio vamos a observar una imagen de un tablero de damas
![TableroDamas](https://png.pngtree.com/thumb_back/fh260/background/20220626/pngtree-chess-or-draught-checker-game-board-board-gameboard-play-photo-image_32104364.jpg)
###
En el tercer ejercicio vamos a enumerar 3 funciones para que el programa quede más claro
###
**crearVariables**
##
"*En esta funcion vamos a crear las variablesque nos hacen falta para el programa*"
#
***Primero creamos el tablero que es un array bidimensional(int tablero[][])***
#
***Despues declaramos las variables: blancas y negras***
#
_Esta función contiene lo principal del programa_
##
**recorrerTablero**
##
"*Para esta funcion necesitamos el tablero y dos variables ajenas (para recorrerlo),i,j*"
#
***Primero recorremos las filas con un bucle for, usando el tablero y la variable i***
#
***Segundo recorrer las columnas con otro bucle for , usando el tablero y la variable j***
#
***Para terminar mostramos tabl[i][j]***
#
_Esto nos retorna las coordenadas de las fichas_
##
**mostrarGanador**
##
"*Para este programa vamos a necesitar la cantidad de blancas y la cantidad de negras que quedan en el tablero*"
#
***Hacemos que el programa tome una decision(if), sobre que color tiene más fichas en el tablero***
#
_Esto nos muestra por pantalla quien es el ganador_
##


