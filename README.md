# iot-pro-heater-cooler
# IoT PRO – Smart Heater & Cooler System

## 📌 Project Overview
IoT PRO is an ESP32-S3 based smart heater–cooler system designed to automatically heat or cool a cup of water using a Peltier (TEC1-12709) module.  
The system measures ambient temperature and allows both **automatic** and **manual control via Wi-Fi web interface**.

## 🎯 Project Objectives
- Measure room temperature using a digital sensor
- Automatically decide heating or cooling based on threshold (20°C)
- Allow user to set target temperature remotely via Wi-Fi
- Display system status on LCD
- Demonstrate IoT concepts for academic purposes

## 🧠 Working Principle
- If temperature **> 20°C** → Cooling mode ON  
- If temperature **< 20°C** → Heating mode ON  
- User can override using web interface

## 🔧 Hardware Components
- ESP32-S3
- TEC1-12709 Peltier module
- Heatsink + cooling fan
- Temperature sensor (DHT22 / DS18B20)
- Relay / BTS motor driver
- 12V Power Supply
- I2C LCD Display
- Thermal paste
- Wires and connectors

## 💻 Software & Technologies
- Arduino IDE
- ESP32 Wi-Fi
- Embedded Web Server
- C / C++

## 🔌 Wiring Diagram
See the wiring diagram in the `wiring/` folder.

## 🌐 Web Interface
The ESP32 hosts a web server allowing:
- Manual temperature input
- Mode switching (Auto / Manual)
- Live temperature monitoring

## 📸 Project Images
![Project Image](images/project_photo.jpg)

## 📚 Educational Use
This project was developed as part of an IoT course and demonstrates real-world application of embedded systems and wireless control.

## 👤 Author
Shohrux Yuldashev  
IoT Course Project – 2026
