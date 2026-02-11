# Nigehbaan – AI-Powered Trip Safety & Crash Detection App

## Overview
Nigehbaan is a native Android safety monitoring application designed to detect emergencies such as crashes, theft/snatching, and abnormal motion using smartphone sensors. The system continuously monitors accelerometer and gyroscope data to identify unusual movement patterns and trigger alerts automatically.

---

## Problem Statement
Road accidents and emergency situations often go undetected due to delayed response. Many safety solutions rely on external hardware or manual triggering. Nigehbaan provides a software-based, real-time monitoring solution using built-in smartphone sensors.

---

##  Features
- Real-time accelerometer & gyroscope monitoring
- G-force based crash detection logic
- Abnormal motion detection (theft/snatching simulation)
- Background sensor monitoring service
- Protected shutdown authentication flow
- Emergency alert trigger mechanism (simulation)

---

## Technologies Used
- Android (Kotlin / Java)
- Android Sensor APIs
- Background Services
- Machine Learning concepts (Anomaly Detection)
- Python (for model experimentation)

---

## Technical Implementation
- Collected and analyzed sensor-based time-series data
- Calculated acceleration magnitude to detect sudden spikes
- Applied threshold-based and anomaly detection logic
- Implemented continuous background service for monitoring
- Designed modular architecture for scalability

---

##  Project Structure
app/
├── activities/
├── services/
├── sensors/
├── utils/
└── models/

## Future Improvements
- Cloud-based alert system integration
- Real-time SMS notification
- Improved ML-based classification model
- Live trip tracking dashboard

---

## Author
Syed Hasan Abbas Naqvi  
BS Software Engineering – FAST NUCES  
