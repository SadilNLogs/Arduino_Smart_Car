# 🚗 Arduino Bluetooth Controlled 4WD Smart Car

## 📖 Project Overview

This project is a **Bluetooth-controlled 4WD robotic car** developed using an **Arduino Uno**, **HC-05 Bluetooth module**, **L298N Motor Driver**, and **four DC geared motors**. The vehicle can move **forward**, **backward**, **left**, **right**, and **stop** through commands sent from an Android Bluetooth controller application.

This project demonstrates practical knowledge in **embedded systems**, **robotics**, **wireless communication**, and **DC motor control**.

---

# ✨ Features

- Bluetooth Wireless Control
- Forward Movement
- Backward Movement
- Left Turn
- Right Turn
- Stop Function
- Four-Wheel Drive (4WD)
- Arduino Uno Based
- Android Smartphone Control

---

# 🛠 Components Used

| Component | Quantity |
|------------|---------:|
| Arduino Uno | 1 |
| HC-05 Bluetooth Module | 1 |
| L298N Motor Driver | 1 |
| DC Geared Motors | 4 |
| 4WD Robot Chassis | 1 |
| Wheels | 4 |
| Battery Pack (12V) | 1 |
| Power Switch | 1 |
| Jumper Wires | Several |

---

# 🔌 Hardware Connections

## HC-05 Bluetooth Module

| HC-05 Pin | Arduino Uno |
|------------|-------------|
| VCC | 5V |
| GND | GND |
| TXD | RX (Pin 0) |
| RXD | TX (Pin 1) |

---

## L298N Motor Driver

| L298N Pin | Arduino Uno |
|------------|-------------|
| ENA | D4 |
| IN1 | D5 |
| IN2 | D6 |
| IN3 | D7 |
| IN4 | D8 |
| ENB | D9 |
| GND | Arduino GND |
| 5V | Arduino VIN/5V *(depending on power configuration)* |
| +12V | Battery Positive |

---

# ⚙ Motor Connections

## Left Side

- Motor 1 → OUT1 & OUT2
- Motor 2 → OUT1 & OUT2

*(Parallel Connection)*

## Right Side

- Motor 3 → OUT3 & OUT4
- Motor 4 → OUT3 & OUT4

*(Parallel Connection)*

---

# 🔋 Battery Connection

Battery Positive → Switch → L298N +12V

Battery Negative → L298N GND

Arduino GND ↔ L298N GND *(Common Ground)*

---

# ⚡ Working Principle

1. The Android application sends Bluetooth commands to the HC-05 module.
2. The HC-05 receives the commands and transmits them to the Arduino Uno.
3. The Arduino processes the received command.
4. According to the command, the Arduino controls the L298N Motor Driver.
5. The motor driver changes the rotation direction of the DC motors.
6. The robotic car performs the requested movement.

---

# 📱 Bluetooth Commands

| Command | Function |
|----------|----------|
| **F** | Move Forward |
| **B** | Move Backward |
| **L** | Turn Left |
| **R** | Turn Right |
| **S** | Stop |

---

# 💻 Software Used

- Arduino IDE
- Bluetooth RC Controller (Android)

---

# 👨‍💻 Programming Language

- C++
- Arduino Framework

---

# 🎯 Skills Demonstrated

- Arduino Programming
- Embedded Systems
- Robotics
- Bluetooth Communication
- Motor Driver Interface
- DC Motor Control
- Electronics
- Circuit Design
- Hardware Integration
- Serial Communication

---

# 🚀 Applications

- Educational Robotics
- Wireless Vehicle Control
- IoT Learning Projects
- Embedded Systems Practice
- Robotics Competitions

---

# 🔮 Future Improvements

- Obstacle Avoidance using Ultrasonic Sensor
- Line Following Robot
- Voice Control
- Wi-Fi Control using ESP32
- Live Camera Streaming
- GPS Navigation
- Mobile Application Development

---

# 📸 Project Images

<p align="center">
  <img src="Components.jpg" width="300">
  <img src="Test4.jpg" width="300">
  <img src="Working.jpg" width="300">
  <img src="Test2.jpg" width="300">
</p>


---

# 🎥 Demo Video

You can upload a demonstration video to YouTube and add the link here.

```
https://youtu.be/V0CKi89dTcM?si=jzslW7gQ86eiZz-v
```

---

# 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Developed By

**Sadil Nethwan**

- BICT Undergraduate – University of Vavuniya
- HND in Electrical Engineering – CINEC Campus

**GitHub:** https://github.com/SadilNLogs

**LinkedIn:** https://www.linkedin.com/in/sadil-nethwan-002489284?utm_source=share_via&utm_content=profile&utm_medium=member_android

⭐ If you found this project useful, please consider giving it a **Star** on GitHub!

