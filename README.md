# CONTROLLING SERVO MOTORS WITH ARDUINO UNO AND AN ANDROID APPLICATION 

In this project, we are going to control two servo motors using an Arduino UNO and an Android app on a mobile device.

# Components Used 

Arduino UNO, HC-06 Bluetooth module, Servo Motors, Connecting wires, Breadboard

# How to Run

Turn ON your mobile Bluetooth and open the Android app. Connect to the Bluetooth module, and when you move the sliders on the app, the servos will move accordingly.

Whenever the slider on the app is moved, the Bluetooth module will send the data from the Android app to the Arduino. The Arduino will get this data through the serial communication.

When the first slider is moved, Arduino receives a value from 0 to 90. We will map this value to 0–180 to move the first servo motor. When the second slider is moved, we will receive the value from 91 to 180. Similarly, we will map this value to move the second servo.

First, make the connections for the servo motors with the Arduino.

Connect the black wire of both the servo motors with the GND of Arduino
Connect the orange wire of both the motors to the 5V of Arduino
Connect the yellow wire of the first motor to pin 9 of Arduino
Connect the yellow wire of the second motor to pin 8 of Arduino
After that, make the connections for the Bluetooth module with the Arduino.

Connect the VCC of the Bluetooth module to 5V of Arduino
Connect the GND of Bluetooth module to the GND of Arduino
Connect the TX of Bluetooth module to pin 10 of Arduino
Connect the RX of Bluetooth module to pin 11 of Arduino

# Applications

The user can control the movement of servo motors with the help of an Arduino UNO and an Android
Application. The following areas where in this concept can be applied are :
1) Opening and Closing of doors automatically
2) Adjusting the Solar Panel according to the changing positions of the Sun
3) Opening and Closing Water Motors automatically in Agricultural Fields



            
