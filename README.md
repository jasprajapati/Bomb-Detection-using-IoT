# Bomb Detection System using IoT

A wireless, Arduino-based bomb detection robot designed for safety-critical environments such as military zones and hazardous areas. The system features a metal detection unit, Bluetooth-based wireless control, and real-time alert capabilities. It was developed and validated as part of the final-year engineering capstone project at K. J. Somaiya College of Engineering.

## 🔧 Project Overview

This robot is intended to detect and remotely identify metallic threats (e.g., bombs or mines) using a custom metal detector circuit. The system is wirelessly controlled via an Android smartphone using a Bluetooth RC controller. Upon detecting metal, the robot halts and triggers visual (LED) and audio (buzzer) alerts to notify the operator.

## 🛠️ Features

- Arduino Nano–based embedded controller
- Custom-designed **metal detector circuit**
- **Bluetooth (HC-05)** module for remote navigation
- **L298N motor driver** for DC motor control
- **Buzzer & LED indicators** for threat signaling
- Full **circuit simulation in Proteus**
- Custom **multi-layer PCB layout** in Altium Designer
- Manual navigation through smartphone app
- Power supply regulation for sensors and actuators

## 🔄 System Workflow

1. Bot is controlled wirelessly using a smartphone app via Bluetooth (HC-05).
2. Robot scans surface using electromagnetic coil and metal detector.
3. If metal is detected:
   - Motors are disabled.
   - A buzzer and LED are triggered.
4. The operator analyzes the area via a connected wireless camera (optional for real use cases).
5. System logs threat information and awaits manual recovery or neutralization.

## 🔬 Technical Specifications

| Component         | Details |
|------------------|---------|
| MCU              | Arduino Nano (Atmega328P) |
| Communication    | Bluetooth HC-05 (Serial) |
| Motor Driver     | L298N Dual H-Bridge |
| Simulation Tool  | Proteus |
| PCB Design Tool  | Altium Designer |
| Power Supply     | 5V for logic, 12V for motors |
| Detection Range  | ~1 meter for ferrous metals |

## 📐 Circuit Design

- **Motor Control Circuit**: Handles directional control via L298N with commands from Arduino.
- **Metal Detector Circuit**: Built around electromagnetic coil and analog readout logic.
- **Alert Circuit**: Activates buzzer and LED when metal is detected.

> Schematics, simulation files, and board layout available under `/hardware` directory.

## 💡 Key Skills Demonstrated

- PCB design (Altium Designer)
- Circuit simulation (Proteus)
- Low-level embedded programmin
