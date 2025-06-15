# FireFightingRobot

# 🔥 Fire Extinguisher Robot

An autonomous + manual firefighting robot designed to detect fire, avoid obstacles, and provide real-time video and location data from hazardous environments.

---

## 🚀 Project Overview

This project combines embedded control, live wireless video, obstacle detection, and GPS tracking to build a remotely operated fire extinguisher robot. It can be used in emergency zones, warehouses, or remote facilities to detect and extinguish small fires with minimal human risk.

---

## 🎯 Features

- 🔥 **Automatic fire detection** (IR flame sensor)
- 🚧 **Obstacle avoidance** using ultrasonic sensors
- 🎮 **Dual-mode control** – Autonomous and manual (via joystick remote)
- 📡 **Live video streaming** using ESP32-CAM
- 📍 **Real-time GPS tracking** with NEO-6M module
- 💧 **Water spray mechanism** with servo motor
- 📶 **Wireless communication** using nRF24L01
- 📊 **Live telemetry**: temperature, water level, battery, fire status, GPS location
- 📺 **LCD Display** on remote unit for status
- 🔋 Battery-powered with status monitoring

---

## 🔧 Hardware Used

### 🧠 Robot Unit
- ATmega32 Microcontroller
- ESP32-CAM (live video)
- NEO-6M GPS Module
- HC-SR04 Ultrasonic Sensor
- IR Flame Sensor
- L298N Motor Driver
- Servo Motors (for water spray & camera pan)
- Water Pump
- nRF24L01 Wireless Module
- Water Level Sensor
- Battery Pack

### 🎮 Remote Controller
- Arduino Pro Mini
- Joystick Module
- Push Buttons & Switches
- 16x2 LCD Display
- nRF24L01 Wireless Module
- Buzzer (alerts)

---

## 🔌 Communication Architecture

- **ESP32-CAM**: Streams live video over Wi-Fi
- **nRF24L01**: Sends/receives telemetry and control commands
- **GPS**: Sends robot location to remote unit
- **Servo**: Controls spray direction and camera movement

---

## 📂 Folder Structure
