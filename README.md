# 🎯 Object Detecting Sensor using Arduino Uno

An **Arduino-based Object Detection System** that uses an **Ultrasonic Sensor** to measure distance and trigger a **Servo Motor** when an object comes within 50 cm.  
This project is ideal for **automation, robotics, and smart security applications**.

---

## 📌 Overview
This project detects nearby objects using the **HC-SR04 Ultrasonic Sensor** and measures the distance in real-time.  
When an object comes within **50 cm**, the servo motor rotates **90°**, and the distance is displayed on the **Serial Monitor**.  
It is **easy to build, cost-effective, and highly practical** for various applications.

---

## ✨ Key Features
- 📏 **Accurate Distance Measurement** using ultrasonic waves
- 🔄 **Automatic Servo Motor Rotation** within detection range
- 🖥 **Real-time Distance Display** via Serial Monitor
- ⚡ **Fast and Reliable** object detection
- 🛠 **Beginner-Friendly** and easy to implement

---

## 🛠 Components Used
| Component | Quantity | Description |
|-----------|----------|-------------|
| Arduino Uno | 1 | Microcontroller board |
| Ultrasonic Sensor (HC-SR04) | 1 | Measures distance using sound waves |
| Servo Motor (SG90) | 1 | Rotates upon detection |
| Breadboard | 1 | For easy wiring |
| Jumper Wires | As required | For connections |
| USB Cable | 1 | For uploading code and powering Arduino |

---

## ⚙️ How It Works
1. **HC-SR04 Ultrasonic Sensor** sends ultrasonic pulses.
2. It calculates the time taken for the pulse to bounce back from an object.
3. Arduino calculates the **distance** using this time.
4. If the object is **≤ 50 cm**:
   - The **servo motor** rotates **90°**.
   - Distance is shown in the Serial Monitor.
5. If the object is farther than 50 cm, the servo resets to its default position.

---

## 🔍 Applications
- 🤖 **Robotics** – Obstacle avoidance systems
- 🏠 **Smart Home Automation** – Automatic gates/doors
- 🚗 **Parking Assistance** – Obstacle distance measurement
- 📦 **Inventory Automation** – Detecting packages on conveyors
- 🔒 **Security Systems** – Motion detection

---

## 🚀 Future Improvements
- 📟 Add an **LCD/OLED display** to show distance
- 🔊 Include a **buzzer alert** for detection
- 📶 Integrate **Wi-Fi or Bluetooth** for IoT applications
- ⚙ Adjustable detection range with a potentiometer

---

