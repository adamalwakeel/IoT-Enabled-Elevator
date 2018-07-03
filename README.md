---
services:	elevator
platforms:	arduino
author:	adam alwakeel
---


# IoT-Enabled-Elevator

## IoT Hub Feather HUZZAH Client application:

### Overview:
Talking to hardware Adafruit Feather HUZZAH ESP8266 and The Arduino Nano  from your development board is when the real fun starts with a project.
However to communicate with other hardware typically requires knowledge of a serial protocol like I2C. These protocol are the common language that chips and add-on boards talk so they can be connected to a development board. The board knows how to ‘speak’ these protocols and control the connected hardware. This guide explores i2c very common serial protocol.

### I2C

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2012.58.43.png)

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2013.16.28.png)



![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2010.13.39.png)

Now the elevator on the floor enter zero number.
Push button 2 Turns on LED 2 The elevator reaches the second floor.

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Sk%C3%A4rmavbild%202018-07-03%20kl.%2010.15.13.png)

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2010.15.29.png)

The elevator is the current second floor and elevator opens door.

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Sk%C3%A4rmavbild%202018-07-03%20kl.%2010.16.07.png)


### In this article Connection between Arduino Nano, Feather HUZZAH ESP8266, and IoT Hub.

 ## What you do Connect Adafruit Feather HUZZAH ESP8266 to an IoT hub that you create. Then you run a sample application on ESP8266 The elevator send message to Azure IOT hub which floor now in real time!! . Finally, you send the message to your IoT hub. 


 ### MQTT Protocol

 In this tutorial we’re going to establish a communication between a Adafruit Feather HUZZAH ESP8266 and an Azure IoT hub  using MQTT.

 MQTT stands for MQ Telemetry Transport and it is a nice lightweight publish and subscribe system where you can publish and receive messages as a client. It is a simple messaging protocol, designed for constrained devices and with low-bandwidth. So, it’s the perfect solution for Internet of Things applications.

![MQTT Protocol](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Mqtt.png)








 