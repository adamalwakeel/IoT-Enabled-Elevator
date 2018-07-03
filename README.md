---
services:	elevator
platforms:	arduino
author:	adam alwakeel
---


# IoT-Enabled-Elevator

## IoT Hub Feather HUZZAH Client application:

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2010.13.39.png)

Now the elevator on the floor enter zero number.
Push button 2 Turns on LED 2 The elevator reaches the second floor.

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Sk%C3%A4rmavbild%202018-07-03%20kl.%2010.15.13.png)

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Ska%CC%88rmavbild%202018-07-03%20kl.%2010.15.29.png)

The elevator is the current second floor and elevator opens the elevator door.

![elevator](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Sk%C3%A4rmavbild%202018-07-03%20kl.%2010.16.07.png)


### In this article Connection between Arduino Nano, Feather HUZZAH ESP8266, and IoT Hub.

 ## What you do Connect Adafruit Feather HUZZAH ESP8266 to an IoT hub that you create. Then you run a sample application on ESP8266 The elevator send message to Azure IOT hub which floor now in real time!! . Finally, you send the message to your IoT hub. 


 ### MQTT Protocol

 In this tutorial we’re going to establish a communication between a Adafruit Feather HUZZAH ESP8266 and an Azure IoT hub  using MQTT.

 MQTT stands for MQ Telemetry Transport and it is a nice lightweight publish and subscribe system where you can publish and receive messages as a client. It is a simple messaging protocol, designed for constrained devices and with low-bandwidth. So, it’s the perfect solution for Internet of Things applications.

![MQTT Protocol](https://github.com/adamalwakeel/IoT-Enabled-Elevator/blob/master/Mqtt.png)








 