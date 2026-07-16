# LUNARIS: Lunar Intelligent Robotic Autonomous System

An advanced autonomous lunar exploration platform designed to simulate operations, navigation, and mapping in extreme environments. 

---

## 🚀 Overview

**LUNARIS** is an intelligent, autonomous robotic rover engineered for simulated lunar exploration missions. The system architecture bridges robust mechanical durability with high-performance edge AI computation to achieve autonomous navigation, obstacle avoidance, and real-time environment mapping.

---

## 🛠️ Key Features

- **Autonomous Edge AI:** Powered by neural processing for real-time terrain evaluation and decision-making.
- **Robust Mobility:** 6-wheel active suspension capable of traversing steep and irregular simulated planetary regolith.
- **Smart Energy Harvesting:** High-efficiency solar array management with dynamic voltage regulation and cell protection.
- **Modular Expansion Framework:** Structured to support future physical payloads and advanced mapping sensors.

---

## 🏗️ Technical Architecture

### 1. Mechanical Design
- **Chassis Framework:** Constructed entirely using **2020 T-Slot Aluminum Extrusions**, delivering an optimal strength-to-weight ratio, structural modularity for easy hardware placement, and natural thermal dissipation.
- **Suspension System:** Utilizes a **6-wheel Rocker-Bogie suspension**, ensuring all wheels maintain continuous ground contact on slopes up to 45° and allowing the rover to climb obstacles twice the wheel diameter.
- **Differential Linkage:** A passive mechanical feedback mechanism that stabilizes and averages chassis pitch, keeping the primary sensor payload perfectly level during rugged climbs.

### 2. Electronic Infrastructure & Core Logic
- **The Brain (High-Level Processing):** **Nvidia Jetson Nano** handles GPU-accelerated parallel data processing, computer vision, and real-time obstacle detection.
- **The Central Controller (Low-Level Processing):** **ESP32 Core Infrastructure** manages real-time motor control loops, sensor stability, and low-latency Wi-Fi/Bluetooth telemetry transmission.
- **Propulsion System:** Driven by **6x independent high-torque DC motors** controlled via industrial-grade H-Bridge drivers featuring real-time current sensing to detect stall states and obstacle resistance.
- **Visual Acquisition:** Equipped with a **Raspberry Pi Camera V2** providing a low-latency HD video feed utilized for distance estimation and path planning.

### 3. Power Management System
- **Energy Storage:** Powered by high-density Lithium-Ion battery packs monitored by an intelligent **Battery Management System (BMS)** that reports the State of Charge (SOC) directly to the ESP32.
- **Solar Array & Charger:** Integrated **Maximum Power Point Tracking (MPPT)** technology optimizing power harvesting from solar cells with a 98% efficiency rate, protecting the battery from overcharging.

---

## 🗺️ Roadmap & Future Scope (Phase II)
- [ ] **3D SLAM Integration:** Incorporating 3D LiDAR scanning to generate precise depth maps of shadowed environments and achieve full localization and mapping autonomy.
- [ ] **Robotic Manipulation:** Integrating a multi-DOF (Degree of Freedom) robotic arm with high-torque digital servos and interchangeable end-effectors for soil and sample collection.

---

