# Adaptive Data Transfer with LoRa for Space 🚀

This project simulates **planet to satellite communication** where a **planetary node** dynamically rotates its antenna using **RSSI feedback** to align with a **space station receiver**. Built using **LoRa, ESP32, Servo Motor, esp-cam**, and environmental sensors like **DHT11**, the system demonstrates adaptive signal optimization in real time and inlcudes various modes to optimize power usage.

## 🌌 Objective
To develop and simulate a LoRa-based communication system for space-like environments that adapts antenna alignment based on signal strength.

## 🛠️ Features
- RSSI-based servo motor control for antenna orientation
- Two-way LoRa communication using ESP32
- Live environmental data transmission (temperature/humidity)
- TFT display for receiver-side monitoring
- Adaptive three modes to extend life
- ESP-cam to capture real-time images
- Secondary memory to safegaurd important data incase of communication failure

## 🧪 Demo Scenario
Simulates a **planet (TX)** to **space station (RX)** communication system on Earth using real-world environmental data.

## 🔧 Components Used
- ESP32-WROOM
- Reyax LoRa modules
- DHT11 sensor
- Servo Motor
- ILI9341 TFT display
- ESP-CAM
- 

## 📁 Code Structure
- `BASIC_RSSI/` – RSSI test code  
- `SERVO+RSSI/` – Servo control using RSSI  
- `TwoWayComW-DHT11/` – Two-way LoRa with sensor data  
- `dht+servo+rssi/` – Integrated antenna control and data transmission

## 📦 Setup Instructions
1. Connect the hardware as per schematic (TBD)
2. Flash `dht+servo+rssi` code on TX ESP
3. Flash receiver display code on RX ESP
4. Observe real-time data and antenna rotation

## 📊 Future Scope
- Automated orbital alignment simulation  
- Integration with satellite emulators  
- AES encryption and QKD modules for secure space comms

---

## 📸 Demo Preview (optional GIF/image)

---

## 🤝 Contributors
- [@alixsaher](https://github.com/alixsaher)

