# 🤖 Line Following Robot using Arduino Uno

An autonomous Line Following Robot built using Arduino Uno, IR sensors, and L298N motor driver for real-time path detection and navigation.

---

## 📌 Project Overview

This project demonstrates the implementation of an intelligent robotic vehicle capable of following a predefined path automatically using IR sensors.

The robot detects a black line on a white surface and adjusts its movement dynamically by controlling two DC motors through an L298N motor driver module.

This project is a practical application of:
- Embedded Systems
- Sensor Integration
- Autonomous Navigation
- Arduino Programming
- Motor Control Systems

---

## 🚀 Features

- Autonomous line tracking
- Real-time path correction
- IR sensor-based detection
- Differential drive control
- Arduino Uno based system
- Compact robotic chassis design

---

## 🛠️ Components Used

| Component | Quantity |
|---|---|
| Arduino Uno | 1 |
| IR Sensor Module | 2 |
| L298N Motor Driver | 1 |
| BO Motors with Wheels | 2 |
| Robot Chassis | 1 |
| Battery Pack | 1 |
| Jumper Wires | Multiple |
| Switch | 1 |

---

## ⚙️ Working Principle

The robot uses two IR sensors mounted at the front side.

- When both sensors detect the black line → robot moves forward
- When left sensor misses the line → robot turns left
- When right sensor misses the line → robot turns right
- When both sensors miss the line → robot stops

The Arduino processes sensor inputs and controls the motors accordingly using the L298N motor driver.

---

## 🔌 Circuit Diagram

![Circuit Diagram](images/wiring-diagram.png)

---

## 📷 Project Images

### Hardware Setup

![Robot Image](images/robot-front.jpg)

---

## 💻 Arduino Code

The complete Arduino code is available in:

```bash
LineFollowingRobot.ino
```

---

## 📂 Documentation

Detailed project report available inside:

```bash
docs/Project_Report.pdf
```

---

## 🧠 Technologies Used

- Arduino IDE
- Embedded C/C++
- IR Sensor Technology
- Motor Driver Control
- Robotics Fundamentals

---

## 🔮 Future Improvements

- PID based line following
- Bluetooth/WiFi control
- Obstacle avoidance
- Camera-based navigation
- AI-based path optimization

---

## 📚 Learning Outcomes

Through this project, I learned:
- Arduino programming
- Sensor interfacing
- Motor control systems
- Autonomous robot logic
- Hardware assembly and debugging

---

## 👨‍💻 Author

Pankaj Kumar

Electronics and Communication Engineering Student

---

## ⭐ Support

If you found this project useful, consider giving this repository a star ⭐
