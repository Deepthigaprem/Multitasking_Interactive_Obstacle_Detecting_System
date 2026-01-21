Multitasking_Interactive_Obstacle_Detecting_System

Obstacle Detection Using Arduino and More..

This project implements a Interactive obstacle detection using arduino uno ,lcd, ultrasonic sensor with alter leds according to the distance and also displays luminousity using photoresistor which are all controlled by ir remote controller.

Component used:
-> Breadboard
-> Jumper wires
-> Arduino uno R3
-> Lcd (I2C)
-> Leds with different colours
-> Resistors(220 ohm ,10K ohm)
-> PushButton 
-> Ultrasonic sensor
-> Photoresistor
-> Ir remote controller

Working Principle: 
1.Blue led blinks according to the distance between the sensor and obstacle.
2.Green led glows according to the luminousity of the atmosphere.
3.Red led glows only when the system is locked,where the system will automatically locked when the obstacle is too close and is unlocked by pushing button.
4.the distance measured and the luminousity is displays in lcd.
5.where the lcd display mode is changed by ir remote controller.

Key Learnings:
1.GPIO control ,timing ,sensor data handling.
2.Structured c/c++ code.
3.Serial communication.
4.Interrupts and button debouncing.

Implementation:
This kind of projects can be implemented as a part of robotics and even in car automation to avoid unaware incidents.

TroubleShooting and FutureImprovements:
~ While using button in the circuit I faced a kind of hardware issue where the system is not responding properly for the button's actions and I resolved it but the concept of button debouncing by changing some code in software.

~ This system can be improved by add sensor and new features.
~ And also it can be made into an iot project with alter messages and can even be controlled by mobilephone.

Author
Deepthigaprem
ECE
