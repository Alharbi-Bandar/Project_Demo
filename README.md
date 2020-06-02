# Project_Demo
Baby Care Security System

I have a Raspberry pi 3 as Master and particle Argon as slave.
The i2c Communications between the two devices.
The raspberry pi has the motion sensor and the magnetic door sensor.
The raspberry pi also has the two LEDs the green LED indicates the system is working and the red LED indicate the door is 
opened. 
When the door is open the LED switch to the red one on the buzzer alarm turn on.
The raspberry pie will communicate with i2c to particle Argon.
When the particle Argon receive a communication from Raspberry pi, it will communicate with IFTTT Software to send a notification through email
to Parent Email to indicate the doors open.
The parent will act to help or provent children from leaving the house. 

