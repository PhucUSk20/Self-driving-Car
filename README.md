# 🤖 SMART ROBOT WAREHOUSE

An autonomous robot system designed for warehouse automation, integrating AI, computer vision, and IoT technologies. The robot enables dynamic route setup via QR Code and MQTT, performs autonomous navigation with deep learning, recognizes different warehouse zones, and supports real-time monitoring through a mobile app and Flask-based web dashboard. Obstacle detection is integrated with automatic stop and Firebase FCM alerts.

---

## 📌 Table of Contents

- [1. Hardware](#1-hardware)
  - [1.1 Autonomous Robot](#11-autonomous-robot)
  - [1.2 Control Dashboard](#12-control-dashboard)
- [2. Robot Operation Overview](#2-robot-operation-overview)
  - [2.1 Route Setup via QR Code](#21-route-setup-via-qr-code)
  - [2.2 MQTT-Based Route Control](#22-mqtt-based-route-control)
  - [2.3 Autonomous Driving (ResNet18)](#23-autonomous-driving-resnet18)
  - [2.4 Area Recognition (AlexNet)](#24-area-recognition-alexnet)
  - [2.5 Sensor System](#25-sensor-system)
  - [2.6 Navigation Algorithm](#26-navigation-algorithm)
  - [2.7 Mobile Application](#27-mobile-application)
- [3. Overview of the Entire System](#3-overview-of-the-entire-system)
---

## 1. Hardware

### 1.1 Autonomous Robot

#### 📌 PCB Layout
![Robot PCB](https://i.imgur.com/F6ePXdl.png)

#### 📌 Schematic Diagram
![Schematic](https://i.imgur.com/EGW568y.png)

#### 📌 Connection Overview
![Connection Diagram](https://i.imgur.com/qbLLM4c.png)

#### 📌 Completed Robot Hardware
![Robot](https://i.imgur.com/oHWf4ct.png)  
![Robot 2](https://i.imgur.com/QmeBiVl.png)

---

### 1.2 Control Dashboard

#### 📌 PCB Layout
![Dashboard PCB](https://i.imgur.com/c9xbmz0.png)

#### 📌 Schematic Diagram
![Dashboard Schematic](https://i.imgur.com/GvETQBo.png)

#### 📌 Hardware Overview
![Dashboard Diagram](https://i.imgur.com/4PNGYPV.png)

#### 📌 Completed Dashboard
![Dashboard](https://i.imgur.com/Buthz7i.png)

---

## 2. Robot Operation Overview

### 2.1 Route Setup via QR Code

![QR Setup](https://i.imgur.com/cyjy5Da.png)

---

### 2.2 MQTT-Based Route Control

![MQTT Control](https://i.imgur.com/G4Yi2zf.png)

---

### 2.3 Autonomous Driving (ResNet18)

#### 📌 Model Training & Implementation

![Driving 1](https://i.imgur.com/JwtFdge.png)  
![Driving 2](https://i.imgur.com/cGcUeYb.png)  
![Driving 3](https://i.imgur.com/slyKwQ8.png)  
![Driving 4](https://i.imgur.com/RQ3R6rP.png)

---

### 2.4 Area Recognition (AlexNet)

![Area 1](https://i.imgur.com/QjqvLu8.png)  
![Area 2](https://i.imgur.com/ZYnyfF5.png)  
![Area 3](https://i.imgur.com/AuU2cnA.png)  
![Area 4](https://i.imgur.com/jpT07Ns.png)

---

### 2.5 Sensor System

![Sensor](https://i.imgur.com/tRw0C3v.png)

---

### 2.6 Navigation Algorithm

![Nav 1](https://i.imgur.com/KmiK5Lu.png)  
![Nav 2](https://i.imgur.com/psggkWD.png)

---

### 2.7 Mobile Application

#### 📌 Socket Server
![Socket 1](https://i.imgur.com/58Nn9hQ.png)  
![Socket 2](https://i.imgur.com/vPoqAms.png)

#### 📌 Flask Backend
![Flask 1](https://i.imgur.com/eEgaKoW.png)  
![Flask 2](https://i.imgur.com/dWUsoJd.png)

#### 📌 Firebase FCM Notifications
![FCM](https://i.imgur.com/Aezp466.png)

#### 📌 Mobile App UI
![UI](https://i.imgur.com/8PXhBDl.png)

---

## 3. Overview of the entire system
![Overview System](https://i.imgur.com/XOSQKXC.png)

## 4. 🎬 Demo

📺 **Project Demonstration Videos**  
Experience the full operation of the Smart Robot Warehouse system, including autonomous navigation, QR-based routing, area recognition, and real-time monitoring:

### 🔗 [Video 1: System Overview & Autonomous Robot Operation](https://www.youtube.com/watch?v=spMlLdgUSRc)

[![Video 1](https://img.youtube.com/vi/spMlLdgUSRc/0.jpg)](https://www.youtube.com/watch?v=spMlLdgUSRc)

### 🔗 [Video 2: Workflow & Dashboard Command Execution](https://www.youtube.com/watch?v=_WNLldl1OI0)

[![Video 2](https://img.youtube.com/vi/_WNLldl1OI0/0.jpg)](https://www.youtube.com/watch?v=_WNLldl1OI0)

> 💡 Click on any image or link above to watch the robot in action — from model training to full system deployment.

## ✅ Technologies Used

- **AI Models**: ResNet18 (Autonomous Driving), AlexNet (Area Recognition)
- **Microcontrollers**: Jetson Nano, ESP32, ESP8266
- **Sensors**: IMU, HC-SR04, MAX30102
- **Communication**: MQTT, Bluetooth, Firebase FCM, Socket
- **Backend**: Flask Server, MQTT Broker
- **Mobile App**: Android (Java), MIT App Inventor
- **Others**: Python, C, Deep Learning, OpenCV

---

## 🙌 Credits

Developed as a final year thesis at **Ho Chi Minh City University of Science (HCMUS)**  
**Team Size**: 2
**Role**: Full-stack Developer, System Designer  
**Duration**: Dec 2023 – Sept 2024

---

