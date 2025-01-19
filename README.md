

# IoT-Based Fire Alert System

An **IoT-based fire detection and alert system** designed to detect fire hazards in real-time using smoke and temperature sensors. The system leverages an ESP32 module for wireless connectivity, sending alerts to a cloud platform for remote monitoring.

---

## Features
- Real-time fire detection using smoke and temperature sensors.
- Wireless data transmission via ESP32.
- Cloud integration for remote monitoring.
- Triggering alerts via notifications, alarms, or dashboards.

---

## Components Used
1. **Hardware**:
   - ESP32 microcontroller.
   - MQ-2 (Smoke Sensor).
   - DHT11/DHT22 (Temperature Sensor).
   - Alarm/Buzzer for local alerts.
   - Power supply.

2. **Software**:
   - Arduino IDE for ESP32 programming.
   - Firebase or any cloud platform for real-time monitoring.

---

## Circuit Diagram
![Circuit Diagram](diagrams/system_architecture.png)

---

## Getting Started

### Prerequisites
1. Install the Arduino IDE: [Download here](https://www.arduino.cc/en/software)
2. Install the ESP32 board package in Arduino IDE.
3. Install required libraries:
   - FirebaseESP32
   - Adafruit DHT Sensor Library

