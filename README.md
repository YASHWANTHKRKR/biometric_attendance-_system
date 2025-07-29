# 🔐 Biometric Attendance System

An easy-to-build biometric attendance system using fingerprint or facial recognition. This project helps you understand how biometric authentication works and how to log attendance data in real-time using a microcontroller and database.

---

## 📌 Project Overview

- **Project Type**: BASIC
- **Duration**: 6 hours
- **Complexity**: Easy
- **Portfolio Worthy**: ✅ Yes

---

## 🎯 Learning Outcomes

- Understand biometric authentication systems.
- Learn how to integrate biometric sensors with a microcontroller.
- Implement real-time data logging into a database.
- Develop practical skills in embedded systems and security.

---

## 🧰 Requirements

### 🔧 Hardware

- Microcontroller (e.g., Raspberry Pi or Arduino)
- Biometric sensor:
  - Fingerprint Sensor (e.g., R305) **OR**
  - Camera Module (for facial recognition)
- USB cable, jumper wires, breadboard (if needed)
- (Optional) LCD display or LED indicators

### 💾 Software

- Arduino IDE or Python 3 (for Raspberry Pi)
- SQLite / MySQL / Firebase (any database for logging)
- Required Libraries:
  - For Arduino: Adafruit Fingerprint library
  - For Python: `face_recognition`, `opencv-python`, `sqlite3`

---

## 🗃️ Database Schema Example (SQLite)

```sql
CREATE TABLE attendance (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    timestamp DATETIME DEFAULT CURRENT_TIMESTAMP,
    status TEXT
);
