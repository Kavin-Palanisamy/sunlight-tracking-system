#  Sunlight Tracking System

An automated **Sunlight Tracking System** designed to improve solar panel efficiency by continuously adjusting the panel toward the direction of maximum sunlight.

## 📌 Project Overview

A fixed solar panel cannot always receive sunlight at the optimum angle throughout the day because the position of the Sun changes continuously.

This project solves this problem by using **Light Dependent Resistors (LDRs)** to detect differences in sunlight intensity. A microcontroller processes the sensor readings and controls a motor to adjust the solar panel toward the direction of stronger sunlight.

The system reduces the need for manual panel adjustment and helps maximize the utilization of available sunlight.

---

## 🎯 Objectives

* Automatically track the direction of sunlight.
* Improve the amount of sunlight received by the solar panel.
* Reduce manual adjustment of the panel.
* Develop a simple and low-cost solar tracking prototype.
* Apply Design Thinking principles to solve a real-world energy problem

---

## 💡 Problem Statement

Conventional fixed solar panels remain at a predetermined angle throughout the day. Since the Sun changes its position continuously, the panel may not always face the Sun directly.

As a result:

* The panel may receive less sunlight.
* Energy generation can be reduced.
* Manual adjustment requires human effort.
* Optimum panel orientation is difficult to maintain throughout the day.

Therefore, an automatic system is required to adjust the solar panel according to the direction of maximum sunlight.

---

## ⚙️ Working Principle

The system uses LDR sensors to compare the intensity of sunlight from different directions.

### Working Process

1. LDR sensors detect the intensity of sunlight.
2. The microcontroller reads the sensor values.
3. The readings from different LDRs are compared.
4. The controller determines the direction with higher sunlight intensity.
5. The motor rotates the solar panel toward that direction.
6. The process continuously repeats as the Sun's position changes.

### Basic Flow

```text
Sunlight
   ↓
LDR Sensors
   ↓
Microcontroller
   ↓
Compare Light Intensity
   ↓
Determine Direction
   ↓
Motor Control
   ↓
Solar Panel Rotation
```

---

## 🔧 Components Used

| Component        | Purpose                                          |
| ---------------- | ------------------------------------------------ |
| Microcontroller  | Processes sensor readings and controls the motor |
| LDR Sensors      | Detect sunlight intensity                        |
| Solar Panel      | Converts sunlight into electrical energy         |
| Servo/DC Motor   | Adjusts the panel position                       |
| Resistors        | Used with LDR sensor circuits                    |
| Power Supply     | Provides power to the circuit                    |
| Connecting Wires | Provides electrical connections                  |
| Supporting Frame | Holds and rotates the solar panel                |

> **Note:** Update this table according to the actual components used in the final prototype.

---

## 🧠 Design Thinking Process

This project follows the Design Thinking methodology.

### 1. Empathize

The user problems related to fixed solar panels, manual adjustment, energy loss, and maintenance were studied.

### 2. Define

The main problem was identified as:

> How can we automatically orient a solar panel toward the strongest available sunlight with minimum human effort?

### 3. Ideate

Different solutions were considered, including:

* LDR-based tracking
* Single-axis tracking
* Dual-axis tracking
* Automatic motor control
* Microcontroller-based control

### 4. Prototype

A working prototype was developed using light sensors, a microcontroller, and a motor mechanism.

### 5. Test

The prototype is tested by observing the panel's movement under different sunlight conditions and checking whether it moves toward the stronger light source.

---


## 🚀 Features

* Automatic sunlight detection
* Automatic panel positioning
* Reduced manual intervention
* Simple control mechanism
* Low-cost prototype approach
* Suitable for educational and experimental applications

---

## 🌱 Applications

The concept can be used in:

* Solar power systems
* Solar-powered irrigation
* Rooftop solar installations
* Remote-area power systems
* Solar charging systems
* Educational renewable-energy projects

---

## ✅ Advantages

* Improves panel orientation toward available sunlight.
* Reduces manual operation.
* Simple control concept.
* Can be implemented using commonly available components.
* Provides practical experience with sensors, motors, and embedded systems.

---

## ⚠️ Limitations

* LDR readings can be affected by clouds and surrounding light.
* Motors consume additional power.
* Mechanical movement requires proper construction.
* Outdoor operation requires protection from rain and dust.
* The actual improvement in energy generation depends on the panel, tracker design, location, and operating conditions.

---

## 🔮 Future Improvements

Future versions of the system can include:

* Dual-axis tracking
* IoT-based monitoring
* Solar power generation measurement
* Battery monitoring
* Mobile/web dashboard
* Automatic fault detection
* Weather-condition monitoring
* GPS-based solar-position calculation
* Energy-efficient motor control

---


## 📊 Expected Outcome

The system is expected to automatically adjust the solar panel toward the direction of stronger sunlight, allowing the panel to maintain a more favorable orientation during daylight hours.

The actual performance improvement should be measured experimentally rather than assuming a fixed percentage increase.

---

## 🛠️ Technologies Used

* Embedded Systems
* Sensors
* LDR
* Microcontroller
* Motor Control
* Solar Energy
* Design Thinking

---


## 📜 License

This project is developed for **educational and academic purposes**.

You may add an appropriate open-source license such as MIT License if you want others to reuse and modify the project.

---

## ⭐ Acknowledgement

This project was developed as an academic project to explore **solar energy, embedded systems, automation, and Design Thinking**.

---

## 🔗 Repository

This repository contains the project documentation, hardware information, source code, circuit design, and project resources required to understand and reproduce the prototype.
