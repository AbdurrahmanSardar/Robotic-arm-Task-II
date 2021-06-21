# Robotic-arm-Task-II

Welcome to the **Robotic-arm-task-II**, In this repository I have design an electronical model to **Control multi servo motors using a potentiometer* and that means varying the angle of the servo motors when varying the potentiometer.

**SHORT BREIF**

I have used _Tinker CAD_ to simulate the model and you can check for the website link at the end of this text.
Short brief of  what I have done through this project. I have connected all the six servo motors with power and ground connection
(red and black wires) from Arduino card **through +5V and GND** ports, and each motor has its unique signal connection with Arduino board (from portpin7 to 12)(orange colored wire of each motor). There are six potentiometers each of them is powered through Arduino card and each of them has its analog portpin (from A0 to A5) as shown in the attached pictures. Each potentiometer controls a unique servo motor.

Then, I have coded it such that each motors move according to a variable value (potentiometer), which means if we changed this value then the angle of the motor will change depending on the value of the variable potentiometer in a range of (0 to 180 degrees).
**NOTE** each line in the code is described in the **ino** file.

**ATTACHMENTS**

Let me introduce all the **attachments** in this repository. There are several files with the following extensions
**brd** file, which is a simulation file from Tinker CAD simulation website.
**ino** file, which is an Arduino code to control all servo motors.
and there are two **PNG** files to show the simulation before and after running the simulation and the code.

If you are working on this in real life please check for the connection of each element carefully as shown in the simulation file of the pictures attached before running for the safety of your tools.

[Tinker CAD link](https://www.tinkercad.com/things/gYsNHfczLtj-multi-servo-motors-with-potentiometers/editel?sharecode=hCVVTLw8NJwAN4ZjHdlSPxn3G3J5PVauyZBgQThzdEA)



