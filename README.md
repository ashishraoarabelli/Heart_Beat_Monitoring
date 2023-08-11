# Heart_Beat_Monitoring
In this project, we'll be creating a simple but effective heartbeat sensor using an Arduino and a pulse sensor. This project is designed to help you understand the basics of sensor interfacing, data acquisition, and visualization.

Introduction : 

The heartbeat sensor is a valuable tool for monitoring a person's heart rate in real-time. It can be used for various applications, such as fitness tracking, health monitoring, and medical research. This project demonstrates how to build a basic heartbeat sensor system using an NODE MCU and a pulse sensor.

Components and software used :
To complete this project, you will need the following components:

NODE MCU (ESP 8266)
Pulse Sensor module
Breadboard and jumper wires
microUSB cable
Arduino IDE and Thingspeak

Procedure : 
1. Copy paste the given code into your Arduino IDE and make changes in the network SSID, Password along with the API Key for the output without errors.
2. Select the board as "NODEMCU 1.0 (ESP 12E Module)" and install the required libraries to make the module get detected. The libraries are
  1. Thingspeak
  2. Pulsesensor Playground
3. Now verify the code and upload it into your module and do the connections as per the references given below and also create an dashboard in Thingspeak and add those values into your code and export it to the module.


Observation : 
1. You can see your output through Arduino IDE's Serial plotter and Serial monitor.
2. With a slight delay, the data will be uploaded to your cloud (Thingspeak dash) and you can monitor your BPM.
