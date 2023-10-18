# IOT
Smart Water Fountain

Phase 1: Project Definition and Design Thinking

 

 The Smart Water Fountains project aims to enhance public water fountains by implementing

IoT sensors to control water flow and detect malfunctions. The primary objective is to

provide real-time information about water fountain status to residents through a public

platform. This project encompasses defining objectives, designing the IoT sensor system,

developing the water fountain status platform, and integrating them using IoT technology

and Python.

Objectives of Smart water fountain 

1. Real-Time Water Fountain Monitoring:Implement IoT sensors to monitor the status of

public water fountains in real-time, including water flow rates and water quality.

2. Efficient Water Usage: Optimize water by detecting anomalies, leaks, or inefficient water

flow patterns.

3. Malfunction Detection: Develop mechanisms to detect malfunctions or maintenance

requirements promptly.

4. Resident Awareness: Create a public platform (e.g., mobile app) to provide residents with

real-time information about water fountain status and quality.

IoT Sensor Design:

1. Sensor Selection: Identify and select appropriate IoT sensors, including flow rate sensors,

pressure sensors, and water quality sensors.

2. Deployment Plan: Plan the deployment of these sensors across public water fountains,

considering factors such as sensor placement, power supply, and connectivity.

3. Data Collection: Determine the data to be collected by each sensor and set the sampling

frequency for real-time monitoring.

Real-Time Water Fountain Status Platform:

1. User Interface Design: Design a user-friendly mobile app interface that displays real-time

water fountain status to users. Include features such as location-based search, status

indicators, and alerts.

2. Data Visualization: Create visually appealing dashboards that provide users with clear and

concise information about water quality, flow rates, and any detected malfunctions.

3. Notification System: Implement a notification system to alert users about issues such as

low water quality or fountain malfunctions.

Integration Approach:

1. Data Transmission: Determine how IoT sensors will send data to the water fountain status

platform. Consider wireless communication protocols, such as MQTT or HTTP, and ensure

data security.

2. Data Processing: Define how data from multiple sensors will be processed, aggregated, and

stored for real-time and historical analysis.

3. IoT Technology: Select the appropriate IoT technology stack, including hardware, software,

and cloud services for data storage and analysis.

Real-Time Water Fountain Monitoring:

- To achieve real-time monitoring, flow rate sensors are deployed at each water fountain to

track water flow rates.

- Pressure sensors are placed within plumbing systems to monitor water pressure.

- Water quality sensors, including pH and turbidity sensors, assess water quality.

Efficient Water Usage:

-Anomalies in water flow rates are detected using flow rate sensors.

- Irregular pressure patterns are identified through pressure sensors.

- The system optimizes water usage by adjusting flow rates based on real-time data.

Malfunction Detection:

- The system employs data from all sensors to detect malfunctions or maintenance needs.

- Flow rate and pressure anomalies indicate potential issues.

- Notifications are sent when malfunctions are detected.

Resident Awareness:

-The mobile app provides residents with real-time data on water quality, flow rates, and

fountain status.

- Alerts and notifications ensure residents are aware of any problems with the fountains.

- Location-based search helps users find nearby water fountains.

IoT Sensor Deployment

Sensor Selection:

- Flow rate sensors: Model XYZ123

- Pressure sensors: Model ABC456

- Water quality sensors: pH Sensor - Model DEF789, Turbidity Sensor - Model UVW987

Deployment Plan:

- Sensors are strategically placed near water outlets and within plumbing systems.

-Sensors are powered by a combination of batteries and solar panels.

- Connectivity is established using Wi-Fi and cellular networks.

Data Collection:

- Flow rate sensors collect data every 5 seconds.

- Pressure sensors sample data every minute.

- Water quality sensors measure pH and turbidity every 15 minutes.

Mobile App Development:

User Interface Design

- The app interface is designed with user-friendliness in mind.

- Location-based search helps users find nearby water fountains.

- Status indicators and alerts provide real-time information.

Data Visualization:

- Dashboards display water quality, flow rates, and malfunction alerts.

- Visualizations are clear and intuitive for users.

Notification System:

- The app features an alert system to notify users of issues.

- Push notifications inform users about low water quality or fountain malfunctions.

Raspberry Pi Integration:

- Raspberry Pi devices serve as edge computing units to process sensor data.

- Python scripts facilitate data transmission between IoT sensors and the central system.

Code Implementation:

- Python is used for sensor data collection, transmission, and analysis.

- Code snippets and diagrams for sensor integration are available in the project's code

repository.

Promoting Water Efficiency and Public Awareness

Water Efficiency:

- Real-time monitoring detects inefficiencies in water flow and pressure.

- Anomalies trigger adjustments to optimize water usage, reducing waste.

Public Awareness:

- The mobile app empowers residents with real-time information.

- Users can make informed choices about water consumption.

- Reporting malfunctions fosters a sense of civic responsibility.

Conclusion:

This documentation provides a comprehensive overview of the Smart Water Fountains

project, covering objectives, sensor setup, mobile app development, Raspberry Pi

integration, and code implementation. It also explains how the system promotes water

efficiency and public awareness.











**Phase 2**

Enhancing Smart Water Fountain Using

IoT Sensors

Components:

Microcontroller:

Arduino or Raspberry Pi for controlling the system.

Sensors:

Ultrasonic sensor, water level sensor for detecting water levels

and user presence.

Actuators:

Water pump, relays for controlling the flow of water.

Wi-Fi Module:

ESP8266 or ESP32 for IoT connectivity.

Indicators:

LEDs, buzzers for indicating water status or system alerts.

Power Supply:

To power the microcontroller and components.

Software:

Arduino IDE:

Programming the microcontroller to read sensor data and

control actuators.

IoT Platform:

ThingSpeak, Blynk, or AWS IoT Core for storing data and

enabling remote monitoring.

MQTT Protocol:

Lightweight messaging protocol for IoT communication.

Data Visualization:

Grafana, Google Charts for real-time visualization.

Mobile App Development (Optional):

Android Studio (for Android apps), Xcode (for iOS apps).

Methods:

Sensor Data Collection:

Use ultrasonic and water level sensors to gather data on water

levels and user presence.

Data Processing:

Process sensor data on the microcontroller to control the

water pump based on readings.

IoT Connectivity:

Integrate Wi-Fi modules for internet connectivity.

Use MQTT protocol for communication between the

microcontroller and IoT platform.

Cloud-Based IoT Platform:

Choose an IoT platform for data storage and remote

monitoring.

Configure the platform to receive and display real-time sensor

data.

Data Visualization:

Utilize Grafana or Google Charts to create visual

representations of sensor data.

User Interaction (Optional):

Develop a mobile app for user control and monitoring.

Alerts and Notifications:

Implement alerts (email, SMS, or app notifications) for

critical events like low water levels.

Testing and Calibration:

Test sensors, actuators, and IoT connectivity thoroughly.

Calibrate sensors for accuracy and fine-tune system parameters.

Documentation:

Document the project comprehensively, including circuit

diagrams, code explanations, and setup instructions.

Maintenance and Support:

Provide guidelines for regular maintenance and

troubleshooting.

Establish customer support channels for user assistance.











SMART WATER FOUNTAIN – PHASE III

INTRODUCTION

In this project, we have created a Smart Water Fountain system that can be controlled remotely 

via a web interface. The system includes components such as NodeMCU ESP8266, Water 

Pump, Relay Module, and Ultrasonic Sensor (HC-SR04). The simulation was done using the 

Wokwi simulator, allowing us to test the functionality of the system virtually.

COMPONENTS USED

1. NodeMCU ESP8266: Microcontroller board.

2. Water Pump: Used to pump water from a container to the fountain.

3. Relay Module: Controls the water pump.

4. Ultrasonic Sensor (HC-SR04): Detects water level in the fountain.

5. Wokwi Virtual Components: Virtual elements used for creating the web interface and 

simulation.

SIMULATION SETUP

1. Wokwi Account: Created a Wokwi account to access the simulation platform.

2. Circuit Configuration: Set up the circuit in the Wokwi Circuit Editor, connecting NodeMCU 

ESP8266, Water Pump, Relay Module, and Ultrasonic Sensor. Virtual components like Button 

and Range were added for the web interface.

CIRCUIT CONNECTIONS (SIMPLIFIED)

1. NodeMCU ESP8266:

 - Connected to Relay Module (Control Pin)

 - Connected to Ultrasonic Sensor (Trigger and Echo Pins)

 - 2. Relay Module:

 - Controls the Water Pump

3. Ultrasonic Sensor (HC-SR04):

 - VCC to 5V

 - GND to GND

 - Trig to NodeMCU GPIO (e.g., D2)

 - Echo to NodeMCU GPIO (e.g., D3)

4. Button (Virtual Component):

 - Connected to NodeMCU GPIO (e.g., D4)

5. Range (Virtual Component):

 - Connected to NodeMCU GPIO (e.g., D5)

ARDUINO CODE

The Arduino code was developed to control the water pump based on user input from the web 

interface and monitor the water level using the Ultrasonic Sensor.

#include <ESP8266WiFi.h>

#include <WiFiClient.h>

#include <Ultrasonic.h>

Const char* ssid = “YourWiFiSSID”;

Const char* password = “YourWiFiPassword”;

Const int trigPin = D2; // Trigger pin of Ultrasonic Sensor

Const int echoPin = D3; // Echo pin of Ultrasonic Sensor

Const int relayPin = D1; // Relay module control pin

Ultrasonic ultrasonic(trigPin, echoPin);

WiFiServer server(80);

Void setup() {

pinMode(relayPin, OUTPUT); 

digitalWrite(relayPin, LOW);

Serial.begin(115200);

WiFi.begin(ssid, password);

While (WiFi.status() != WL_CONNECTED) {

 Delay(1000);

 Serial.println(“Connecting to WiFi...”);

 }

Server.begin();

}

Void loop() {

WiFiClient client = server.available();

If (client) {

 String request = client.readStringUntil(‘\r’);

 If (request.indexOf(“/on”) != -1) {

 digitalWrite(relayPin, HIGH); // Turn the pump on

 delay(2000); // Run the pump for 2 seconds

 digitalWrite(relayPin, LOW); // Turn the pump off

 }

 Client.flush();

 }

 // Check water level

 Float distance = ultrasonic.read();

 If (distance < 10) {

 // Water is low, update the web interface

 // You can send an HTML response to the client here

 }

}

SIMULATION AND TESTING

1. Code Implementation: Implemented the Arduino code to control the water pump and monitor 

water level.

2. Simulation: Clicked the "Simulate" button in Wokwi to start the simulation.

3. Testing: Interacted with the virtual components in the simulation to test the system's 

functionality.

CONCLUSION

The Smart Water Fountain system simulation was successfully carried out using the Wokwi 

simulator. The system demonstrated remote control capabilities and real-time monitoring of 

the water level. This simulation provides a basis for further development and implementation 

in real-world IoT projects.
