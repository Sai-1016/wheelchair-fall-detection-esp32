# ♿ IoT Wheelchair Fall Detection System

## 🔹 Overview
An IoT device that detects **wheelchair falls** using **ESP32 Microcontroller + MPU6050 Sensor** and notifies caregivers via the **Blynk IoT Platform**.  

The system also captures images **10 seconds before & after** the incident, providing **context for accident analysis**.

## 🔹 System Architecture
![Wheelchair Fall Detection Architecture](docs/wheelchair_fall_architecture.png)

## 🔹 Features
- 📡 Real-time fall detection using MPU6050 accelerometer & gyroscope  
- 📷 Captures images pre/post incident for cause analysis  
- ⚡ Alerts sent instantly via **Blynk IoT mobile app**  
- 🛡️ Designed for elderly & disabled preventive care  

## 🔹 Repository Structure
```
/firmware     # ESP32 + MPU6050 code
/blynk        # Dashboard configuration
/docs         # Architecture diagrams, demo images
```

## 🔹 Author
👨‍💻 **Sai Sudarshan S**  
B.Tech CSE | IoT & ML Enthusiast | Published Author (CRC Press)
