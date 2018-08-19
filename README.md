# -PRYK---NodeJSArduinoFRLNC
Proyecto desarrollado en Node JS con comunicación bidireccional con Arduino.

*Cosas a considerar para el deploy de la aplicación, se requieren de **ciertas** librerias* ***buscar en internet como lograrlo***
* Instalar **NodeJS** desde consola 
* Una vez con los comandos de NodeJS instalar las siguientes expansiones a través de **npm**.
  * Instalar **Express** con un comando como ***node install espress***
  * Instalar **SerialPort** con un comando como ***node install serialport***
  * Instalar **socket.io** con un comando cómo ***node install socket.io***
  
##### Cómo agregar *modals* para msotrar información en la página.
Para agregar *modals* debes módificar el archivo ***index.html*** en la sección de códigos con **id** con el nombre *modal*.

##### Cómo agregar *condiciones* en el código JavaScript para mostrar o no los *modals*
Para agregar condiciones debes módificar el archivo **/js/main.js** en la sección del *swith* y puede sentirte libre de agregar cuantas condiciones desees o necesites para mostrar ( ***hide*** o ***show*** ) los *modals* que previamente estableciste en el archivo ***index.html***

##### ADVERTENCÍA
**NO** es recomendable modificar el archivo ***node/node.js*** es el servidor, para echar a andar el proyecto debes situarte en la carpeta raiz; en este caso **NodeJSArduino/** y ejecutar el comando a través de la consola y Node JS previamente instalado:

### *node node/node.js*
El comando es *node* y ejecutas el servidor que está en el archivo *node.js* dentro de la carpeta *node*
