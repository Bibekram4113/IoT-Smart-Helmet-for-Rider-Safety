# IoT-Smart-Helmet-for-Rider-Safety


An **IoT-enabled smart helmet** that enhances rider safety by integrating **crash detection, GPS tracking, health monitoring (pulse & temperature), air-quality sensing, and cloud-based alerts**. This system ensures real-time safety monitoring and emergency response for riders.  

---

## 🎯 Features  
- 🚨 **Crash Detection** using accelerometer + gyroscope  
- 📍 **GPS Tracking** for real-time accident location alerts  
- ❤️ **Health Monitoring** (pulse rate & body temperature sensors)  
- 🌍 **Air Quality Monitoring** with gas sensors (pollution tracking)  
- ☁️ **Cloud Integration** for real-time monitoring and emergency alerts  
- 🖥️ Custom **PCB Design** for compact and reliable system integration  

---

## 🛠️ Hardware & Components  
- **Microcontroller**: Arduino Nano  
- **Sensors**:  
  - MPU6050 – Accelerometer & Gyroscope (crash detection)  
  - GPS Module (location tracking)  
  - Pulse Sensor (heart rate)  
  - LM35 / DS18B20 (temperature)  
  - MQ-135 (air quality monitoring)  
- **Connectivity**: IoT cloud platform (ThingSpeak / Firebase)  
- **PCB**: Custom-designed for integrating all modules  


📂 Methodology

Sensor Integration → Collect rider health, crash, and environment data

Data Processing → Arduino Nano analyzes crash impact + sensor values

Cloud Transmission → IoT platform uploads real-time data

Alerts & Dashboard → Notifications sent to emergency contacts + live dashboard monitoring

▶️ Usage

Assemble hardware with helmet (PCB + sensors + Arduino Nano).

Upload firmware to Arduino Nano from /code/helmet.ino.

Connect to IoT cloud (ThingSpeak / Firebase).

Monitor dashboard for real-time rider status & alerts.

📊 Results

Crash detection accuracy: ~95% in testing

Emergency alert delivered within 3–5 seconds

Real-time monitoring of health + environmental conditions

🔮 Future Work

Integrate voice-assisted SOS calling (e.g., GSM module)

Add fatigue detection using EEG / eye-tracking

Deploy a mobile app for live rider health & safety analytics

Optimize system for low power consumption
