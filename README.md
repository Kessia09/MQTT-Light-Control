# MQTT Light Control

This project is a web-based application that allows a user to switch a light ON/OFF using MQTT. The application consists of:

## Features
- A simple web interface (`index.html`) with ON/OFF buttons that publish MQTT messages.
- A Python script (`light_simulation.py`) simulating an IoT device (ESP8266) that listens for MQTT messages and prints the light status.
- Uses a public MQTT broker (`test.mosquitto.org`) for communication.

## How to Run
1. Open `index.html` in a browser.
2. Run `light_simulation.py` to listen for messages.
3. Click the buttons on the webpage and observe the light status updates in the terminal.

## Technologies Used
- MQTT.js for client-side communication
- Paho MQTT for Python-based IoT simulation
- WebSockets for MQTT communication
