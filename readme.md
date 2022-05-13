## Practica: API REST Trello

Para la creacion de esta practica el primer paso fue registrarme en trello y acceder a la seccion de developers para obtener la KEY y el TOKEN.

### 1. Creación de tablero (metodo POST)
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/1CreateBoardPostman_LI.jpg)
Los parametros que utilice para la creacion del tablero fueron:
1. name 
2. key
3. token

En name se le asigna el nombre que le deseemos asignar al tablero.
### 1. Y asi queda: 
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/1Showboardtrello.PNG)
 
 
### 2. Aqui se muestran las listas que tenemos en nuestro tablero (metodo GET). 
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/2CreateCardbylistId.PNG)
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/2showboard.PNG)

### 3. Aqui se crean las listas que tenemos en nuestro tablero. (Metodo POST).
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/3Createcardbylistid.PNG)
y se ve el resultado en el tablero:
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/3ShowlistId.PNG)

### 4. Aqui se actualizan las listas seleccionadas por el ID. (Metodo PUT).
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/4Updatecardbyid.PNG)
y se ve el resultado en el tablero:
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/4ShowUpdatecard.PNG)

### 5. Aqui se eliminan las listas seleccionadas por el ID. (Metodo DEL).
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/5DeleteCardbyId.PNG)
![Texto alternativo](https://github.com/jorgealexis07/apiresttrello/blob/main/images/5Showdelete.PNG)

