# Door Dimmer - AUTOSAR Compliant

The system checks wether any car door is opened to turn on the dimmer lamp, or to turn it off if they are all closed.  

The project is applied on `AVR ATmega32` using tacktile switch for each door and a lamp 

## Project Architecture
AUTOSAR compliant using one ECU for basic implementation, following the next architecture: 

 <p align="center">
  <img  src="../media/layered architecture.png?raw=true">
</p>

## Hardware Connections
1- Switch representing right door -> PORT A, Pin 0   
2- Switch representing left door -> PORT A, Pin 1   
3- Lamp -> PORT A, Pin 2      

Note: Switches are connected with pull up resistors

