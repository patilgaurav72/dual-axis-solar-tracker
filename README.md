# 🌞 Dual Axis Solar Tracker

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-NodeMCU-orange)
![IoT](https://img.shields.io/badge/IoT-Firebase-red)

A **Dual Axis Solar Tracker** that automatically adjusts the position of a solar panel to maximize sunlight capture.  
The system uses **LDR sensors** to detect light intensity and **servo motors** to align the panel both horizontally and vertically.  
Powered by **NodeMCU (ESP8266)**, it also supports **IoT data logging** to Firebase for real-time monitoring.

---

## 🚀 Features
- 🌍 **Dual Axis Tracking** – Tracks the sun both horizontally (azimuth) and vertically (elevation).  
- ☀️ **LDR Sensor Array** – Four LDRs detect maximum light intensity.  
- ⚙️ **Automatic Servo Control** – MG995/MG996R servo motors adjust the panel.  
- 📡 **IoT Integration** – Sends data to Firebase in real time.  
- 🔋 **Energy Efficiency** – Powered by a 10W solar panel with LiPo charging.  
- 💡 **LED Indicator** – Lights up when panel generates output.  

---

## 🔧 Components Used
- **NodeMCU (ESP8266)** – WiFi-enabled microcontroller.  
- **4 × LDR Sensors** with resistors.  
- **2 × Servo Motors (MG995/MG996R)**.  
- **10W Solar Panel**.  
- **TP4056 Charging Module** – LiPo charging.  
- **XL6009 DC-DC Step-up Converter**.  
- **LM2596 Buck Converter**.  
- Breadboard, jumper wires, LEDs, resistors.  

---

## ⚡ Circuit Diagram
📷 *Add your circuit diagram here*  
