# Smart-Fish_Feeder_IoT

# 🐟 Smart Fish Feeder (Automatic Fish Feeding System)

## 📌 Project Overview
The **Smart Fish Feeder** is an IoT-based project that automatically feeds fish on a scheduled basis.  
It is built using an **ESP32 microcontroller** and a **servo motor**, with time synchronization handled via **NTP (Network Time Protocol)**.  

This project is designed to reduce manual effort and ensure fish are fed consistently at fixed times, such as morning and afternoon.

---

## ⚙️ Features
- ⏰ Automatic feeding at scheduled times (07:00 & 17:00 by default)  
- 🌐 Time synchronization with NTP server (via WiFi)  
- ⚡ Simple and energy-efficient design  
- 🔧 Easy to modify feeding schedule and servo angle  

---

## 🛠️ Hardware Requirements
- ESP32 Development Board  
- Servo Motor (SG90 or similar)  
- WiFi connection  
- Power supply (5V recommended)  

---

## 📦 Software & Libraries
Make sure you have the following installed in Arduino IDE:
- `WiFi.h`  
- `ESP32Servo.h`  
- `NTPClient.h`  
- `WiFiUdp.h`  

---

## 🚀 How It Works
1. ESP32 connects to WiFi.  
2. Current time is retrieved from the **NTP server**.  
3. At the scheduled hours (07:00 & 17:00), the servo rotates to release food.  
4. Servo returns to the default position after 2 seconds.  

---

## 👨‍💻 Author
**Mohammad Alwi Ferdiansyah Alfarizi**  
- 🎓 Electronics Engineering Student (Politeknik Negeri Malang, Kediri Campus)  
- 💡 Passionate about IoT, Robotics, and Smart Technology  

---

## 📜 License
This project is open-source and available under the **MIT License**.  
Feel free to use, modify, and share. 🚀


