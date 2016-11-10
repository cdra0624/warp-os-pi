# Warp OS for Raspberry Pi 3 #

### What is this repository for? 
Control arduino and iRobot create2 from remotely using Raspberry Pi.

![yellowLine](client/assets/images/yellowLine.png)

### How do I get set up? ###

```sh
$ git clone path
$ cd path
$ npm install
$ npm start
```
:warning: You have to connect arduino first and roomba serial cable.  

![yellowLine](client/assets/images/yellowLine.png)
### Dependencies     
Node : ver 4.6.1  
Serialport : ver 2.1.2  

![yellowLine](client/assets/images/yellowLine.png)
### Index    
**01-1. led blink**  
Simple LED blink sample.  
Local demo : http://localhost:PORT/01-1.ledBlink/  
```sh
$ node debugger.js
```  

**01-2. slider for servo control**   
control servo using simple slider  
Local demo : http://localhost:PORT/01-2.sliderServo/   
```sh
$ node debugger.js
```  

**02-1. roomba local controller**   
control roomba from local    
Local demo : http://localhost:PORT/02-1.roombaController/   
```sh
$ node roombaDebugger.js
```  
:warning: please check correct path to roomba    
Raspberry Pi : /dev/ttyUSB0  
Mac OSX : dev/cu.usbserial-DA01NMCP
```sh
$ ls /dev | grep tty
```  

![yellowLine](client/assets/images/yellowLine.png)

### References ###
[adawarp.com](http://adawarp.com/)  

