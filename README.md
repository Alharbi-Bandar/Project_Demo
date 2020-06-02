# Project_Demo
Baby Care Security System is a system that solves a real-world problem. 

Problem statement:

What is Baby Care Security System:
Baby care system is a system that helps preventing childerns from leaving home without parents noticing. The idea is to install the system into a device and place that device on top of the house door. When the device is activated, whenever the house door is opened parents will be notified through a sound alarm or a text to their mobile devices. This can help parents protect their childrens from leaving home without their notice.

If Children leave the home without parnet notice, this could go many different ways.
Especially kids in age between (2 to 5) can do things without knowing the consequences of their actions. Therefore, it is the parents responsibility to guard them all the time, and with the help of Baby Care Security System this can be achieved.

The solution:
Baby Care Security System purpose is to notify the parents whenever the door is open through an email message and a sound alarm.
I will build the system to modify me if the child has opened the door. 
The system will send me a notification message that the door is opened. 

The connections:
I have a Raspberry pi 3 as Master and particle Argon as slave.
With the use of i2c communication between master Rasberry Pi3 and slave particle Argon devices. The motion sensor and magnetic sensor will be attached to the Rasberry Pi3 and placed on top of the door. 
The Raspberry pi3 also has the two LEDs the green LED indicates the system is working and the red LED indicate the door is 
opened. When the door is open the LED switch to the red one and communicate with Particle Argon that the system is activated. Additionally, a feature is added to the system that when the door ramins opened for a period of time, a sound alarm will turn off to notify the parents.
The particle Argon will use IFTTT software to notify the parents when the door is opened. 

Final result:
Therefore, the parent will act to help or provent children from leaving the house. 


