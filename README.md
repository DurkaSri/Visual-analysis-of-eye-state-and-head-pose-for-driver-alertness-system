# 🚗 VISUAL ANALYSIS OF EYE STATE AND HEAD POSE FOR DRIVER ALERTNESS MONITORING SYSTEM

This project implements a Driver Alertness Monitoring System using visual analysis of eye state and head pose. Using camera‑based detection and a microcontroller interface, the system identifies driver fatigue, drowsiness, or distraction and triggers real‑time alerts to enhance road safety.

The system analyzes:

Eye openness/closure using facial landmark detection
Head pose variations (pitch, yaw, roll)
Microcontroller‑based alert mechanisms (buzzer, GSM/SMS, etc.)
Its goal is to reduce road accidents caused by driver fatigue by providing timely alerts and monitoring

---

## 📘 Project Overview
The system captures live video and processes:
- Eye state (open/closed)
- Head pose (pitch, yaw, roll)
- Drowsiness detection and alert generation

---

## 🛠️ Hardware Components
- Microcontroller (Arduino / ESP32 / STM32)
- Camera (USB Webcam / Pi Camera / OV5647)
- Buzzer / Speaker for alerts
- GSM/GPS module (optional)
- LCD module (optional)
- Power supply & connecting wires 

---

## 🧠 Software Used
- OpenCV
- dlib / MediaPipe
- NumPy
- imutils
- pySerial (microcontroller communication)

---

## ⚙️ Flow Diagram

![Flow Diagram](./flow%20diagram.jpeg)

---

## 📊 Documents

### 📄 Report  
Click to view/download:  
👉 **[Driver Alertness Project Report](./report.pdf)**

### 📊 PPT  
Click to view/download:  
👉 **[Alertness Monitor PPT](./alertness%20monitor.pptx)**

## 📈  Features

- Real‑time driver monitoring
- Eye closure detection
- Head pose estimation
- Microcontroller‑based alerting system
- Expandable for IoT and cloud integration

## 🚀 Future Enhancements

- Integration with vehicle CAN bus
- Mobile app for live streaming driver status
- Cloud storage for long‑term monitoring
-  Advanced deep‑learning eye-state classification
