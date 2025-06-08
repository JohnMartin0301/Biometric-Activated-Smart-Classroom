# Biometric Activated Smart Classroom

## Introduction

This project is a **smart classroom system** designed for enhanced **security**, **automation**, and **efficiency**. It uses **biometrics (fingerprint)** and **RFID technology** to manage access to the room and equipment, and includes features like **IoT-based intrusion alerts**, **automatic device control**, and **CCTV surveillance**. 

---

![Biometric-Activated Smart Classroom](https://github.com/user-attachments/assets/512086fc-2c0d-443a-bb52-5a304348b961)

## Features and Functionalities

### Biometric Door Access
- Professors/lab staff use their **fingerprint** to unlock and open the door.
- **Lights, fans, and air conditioner** turn on automatically when they enter.
- Door **closes by itself** after entry.
- **Students can only enter** if a professor/lab staff is already inside.
- **Access is denied** if no staff is present.

---

### Break Timer
- Users can take a **short break (15 seconds max)**.
- If the user doesn’t return within 15 seconds:
  - Their **access is temporarily blocked**.
  - System **resets access** after the session ends.

---

### Tailgating Detection
- The system can detect **multiple people entering/exiting together**.
- If tailgating is detected:
  - An **alarm sounds**.
  - Only professors/lab staff can **reset the alarm**.

---

### Smart Exit
- Professors/lab staff can only exit if **no students are inside**.
- When the last person exits:
  - **Lights, fan, and AC** turn off.
  - **Door locks automatically**.

---

### RFID Equipment Monitoring System
- Users can **borrow and return equipment** by tapping their **RFID cards**.
- Equipment has **RFID tags**.
- The system:
  - **Logs who borrowed what and when**.
  - Can **detect theft** if items are taken without permission.

---

### IoT-Based Intrusion Detection (with RainMaker App)
- Sends **real-time alerts** if someone tries to enter without permission.
- Controlled via **ESP RainMaker app** (on/off).
- **Sends a reminder every minute** if the intrusion system is off and should be on.
- Also **sounds an alarm** when an intrusion is detected.

---

### CCTV Surveillance
- Uses an **ESP32-CAM** to monitor the classroom.
- Provides **live video feed** for additional security.

---

## How It Works (Simplified)
- The system checks **fingerprints** to open the door and turn on the room devices.
- Students can only get inside if a **professor/staff is already there**.
- **RFID** is used to keep track of borrowed/returned equipment.
- **PIR sensors and ESP32** are used to detect intrusions.
- Notifications and remote control are done through the **RainMaker mobile app**.
- A **camera module (ESP32-CAM)** watches over the classroom for surveillance.

---

## Source Code

The **source code is not available** in this repository.

> This system was developed as a **final year project**. The source code is **not being shared publicly** to maintain the **originality and confidentiality** of the work.
