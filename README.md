# Adaptive Data Transfer with LoRa for Space 🚀

This project simulates **planet to satellite communication** where a **planetary node** dynamically rotates its antenna using **RSSI feedback** to align with a **space station receiver**. Built using **LoRa, ESP32, Servo Motor, esp-cam**, and environmental sensors like **DHT11**, the system demonstrates adaptive signal optimization in real time and inlcudes various modes to optimize power usage.

## 🌌 Objective
To develop and simulate a LoRa-based communication system for space and space-like environments that adapts antenna alignment based on signal strength, has adaptive power modes and includes imagery transmission wirelessly.

## 🛠️ Features
- RSSI-based servo motor control for antenna orientation
- Two-way LoRa communication using ESP32
- Live environmental data transmission (temperature/humidity)
- TFT display for receiver-side monitoring
- Adaptive three modes to extend life
- ESP-cam to capture real-time images
- Secondary memory to safegaurd important data incase of communication failure

## 🔧 Components Used
- ESP32-WROOM
- Reyax LoRa modules
- DHT11 sensor
- Servo Motor
- ILI9341 TFT display
- ESP-CAM
- GY-91 sensor
- 3.7V battery

## 📁 Code Structure
- `BASIC_RSSI/` – RSSI test code  
- `SERVO+RSSI/` – Servo control using RSSI  
- `TwoWayComW-DHT11/` – Two-way LoRa with sensor data  
- `dht+servo+rssi/` – Integrated antenna control and data transmission


## 🤝 Contributors
- [@alixsaher](https://github.com/alixsaher)
- [@pushhpa31](https://github.com/pushhpa31)

