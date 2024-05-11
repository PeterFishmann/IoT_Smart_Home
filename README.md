# IoT Smart Home System

## Project Overview
This project is a miniature version of a smart home system designed to run on a Raspberry Pi and ESP32. Developed collaboratively by Yassine El Yamani, Mégane Kickouama, Peter Isaac Fishman, and Ilan Trutner, it features various functionalities necessary for smart home automation and monitoring.

## Features
- **RFID Tag Scanning:** Utilizes an RFID chip scanner to identify users. Data from scanned tags are sent to the Raspberry Pi via Mosquitto client for verification against a database of known tags.
- **Email Notifications:** Sends confirmations and updates to users about system status and other alerts. Users need to configure their email credentials to enable this feature.
- **LED Control:** Includes functionality to turn on and adjust an LED for lighting.
- **Motor Control:** Controls a motor used to simulate a fan.
- **Humidity and Temperature Reading:** Utilizes a DHT11 sensor to monitor and record temperature and humidity conditions.
- **Bluetooth Scanning:** Capable of detecting nearby Bluetooth devices.
- **Light Intensity Monitoring:** Incorporates a photoresistor to measure light intensity, sending this data to a Mosquitto client for processing.

## Hardware Requirements
The system is built using the following components, detailed in the accompanying Fritzing file:
- Raspberry Pi
- ESP32
- RFID Scanner
- DHT11 Sensor
- LED
- Motor
- Photoresistor
- Miscellaneous wiring and resistors for connections

## Usage
- Run the main scripts to start the system
- Place RFID tags near the scanner to log activity and test the system's responsiveness.
- Observe the output from the LED, motor, DHT11 sensor, and photoresistor.

## Collaboration
**This project is the result of a collaborative effort among:**

- *Yassine El Yamani*
- *Mégane Kickouama*
- *Peter Isaac Fishman*
- *Ilan Trutner*

## License
This project is licensed under the MIT License - see the 	[LICENSE.md](LICENSE) file for details.
