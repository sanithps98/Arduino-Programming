# Controlling Servo Motors with Arduino UNO and an Android Application

In this project, we are going to control two servo motors using an Arduino UNO and an Android app on a mobile device.

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

# How to Run

Turn ON your mobile Bluetooth and open the Android app. Connect to the Bluetooth module, and when you move the sliders on the app, the servos will move accordingly.



            
