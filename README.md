# -PRYK---NodeJSArduinoFRLNC
Proyecto desarrollado en Node JS con comunicación bidireccional con Arduino.

*Cosas a considerar para el deploy de la aplicación, se requieren de **ciertas** librerias JavaScript*; ***se puede buscar en internet de cómo lograr instalarlas***
* Instalar **NodeJS** desde consola 
* Una vez con los comandos de NodeJS se deben instalar las siguientes librerias JavaScript a través de **npm**.
  * Instalar **Express** con un comando como ***node install espress***
  * Instalar **SerialPort** con un comando como ***node install serialport***
  * Instalar **socket.io** con un comando cómo ***node install socket.io***
  
##### Cómo agregar *modals* para mostrar información en la página.
Para agregar *modals* se debe modificar el archivo ***index.html*** en la sección de códigos con **id** con el nombre *modal*.

##### Cómo agregar *condiciones* en el código JavaScript para mostrar o no los *modals*
Para agregar condiciones se debe módificar el archivo **/js/main.js** en la sección del *swith* y se tiene la libertad de agregar cuantas condiciones se desee o se necesite para mostrar ( ***hide*** ó ***show*** ) los *modals* que previamente se estableció en el archivo ***index.html***

##### ADVERTENCÍA
**NO** es recomendable modificar el archivo ***node/node.js*** es el servidor, para echar a andar el proyecto se debe situar en la carpeta raiz; en este caso **NodeJSArduino/** y ejecutar el comando a través de la consola y Node JS previamente instalado:

### *node node/node.js*
El comando es *node* y ejecutas el servidor que está en el archivo *node.js* dentro de la carpeta *node*
