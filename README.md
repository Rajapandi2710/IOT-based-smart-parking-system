# IOT-based-smart-parking-system
The idea goes through the method of Placing a PIR sensor on top of a parking Slot and an IR sensor in front of the Slot and the changes are updated in the Blynk Server.

**Materials Needed:**
NodeMCU or other ESP8266-based development board
Breadboard and jumper wires
PIR (Passive Infrared) sensor
IR (Infrared) sensor
Smartphone with Blynk app installed

**Project Description:**
**Hardware Setup:** Connect the NodeMCU module to the breadboard and provide power (3.3V) and ground connections. Connect the PIR sensor to the NodeMCU's GPIO pins and the IR sensor to the corresponding pins.
**NodeMCU Code:** Write code for the NodeMCU using the Arduino IDE. The code should initialize the PIR and IR sensors, detect occupancy based on the sensor readings, and update the status in the Blynk app using the Blynk library.
**Blynk App Setup**: Set up a new Blynk project, add the NodeMCU device, and create a virtual pin to display the parking slot occupancy status.
**Testing and Operation:** After setting up the hardware, installing the necessary apps, and writing the code, test the system by placing objects or vehicles in the parking slot. The sensors should detect occupancy and update the status in the Blynk app.

This project demonstrates how you can use a NodeMCU development board, PIR and IR sensors, and the Blynk app to monitor parking slot occupancy. By placing the PIR sensor on top of the parking slot and the IR sensor in front of the slot, you can accurately detect whether the slot is occupied or not. The Blynk app allows you to check the occupancy status remotely, making it a convenient solution for parking management.
