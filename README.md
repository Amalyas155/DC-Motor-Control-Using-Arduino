# 🚗 DC Motor Control Using Arduino Uno

Control a DC geared motor using **Arduino Uno** and the **L298N Motor Driver Module** with an external battery supply.

---

## 📸 Project Preview

<img width="1215" height="1295" alt="4d2bfa4e-3d8b-4ceb-8d67-3c4ff46214d8" src="https://github.com/user-attachments/assets/f8e7d1b8-5446-4083-9f4b-53da30eeeba7" />



---

## 📖 Project Overview

This project demonstrates how to control a DC geared motor using an Arduino Uno and an L298N Motor Driver.

The Arduino sends digital control signals to the motor driver, while an external battery pack provides the required power for the motor. The motor rotates forward and backward with programmed delays, making this project a simple introduction to DC motor control used in robotics.

---

## 🛠️ Components

| Component | Quantity |
|-----------|:--------:|
| Arduino Uno | 1 |
| L298N Motor Driver | 1 |
| DC Geared Motor | 1 |
| Robot Wheels | 2 |
| Battery Holder | 1 |
| AA Batteries | 2 |
| Jumper Wires | Several |
| USB Cable | 1 |

---

## 🔴 Motor Driver

The red module shown in this project is the **L298N Motor Driver Module**.

It acts as an interface between the Arduino and the DC motor by supplying enough current for the motor while allowing the Arduino to control:

- ▶️ Forward rotation
- ◀️ Reverse rotation
- ⏹️ Stop
- ⚡ External motor power

---

## 🔌 Wiring

| Arduino | L298N |
|---------|--------|
| Pin 8 | IN1 |
| Pin 9 | IN2 |
| GND | GND |

| Motor | L298N |
|--------|--------|
| Wire 1 | OUT1 |
| Wire 2 | OUT2 |

| Battery | L298N |
|----------|--------|
| Positive (+) | 12V / VIN |
| Negative (-) | GND |

> **Note:** The Arduino and the L298N must share the same GND.

---

## ⚙️ How It Works

1. Arduino sends HIGH/LOW signals.
2. L298N receives the signals.
3. The motor rotates forward.
4. The motor stops.
5. The motor rotates backward.
6. The sequence repeats continuously.



---

## 💡 Applications

- 🤖 Robotics
- 🚙 Smart Car Projects
- ⚙️ Motor Control
- 📚 Arduino Learning
- 🎓 Engineering Labs



---

## 👩‍💻 Author

**Amal Yasser**
