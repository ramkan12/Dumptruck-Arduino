# Autonomous Arduino Dump Truck

<div align="center">
  
![Dump Truck](images/truck_main.jpg)

**An educational hands-on robotics project designed for K-12 students to learn engineering principles**

[🎥 Watch Demo](https://www.youtube.com/watch?v=MdCv9IWylZ0) • [📄 Full Documentation](docs/Showcase_Portfolio.pdf) • [⚡ Quick Start](#-quick-start)

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Educational](https://img.shields.io/badge/Educational-K--12-orange?style=for-the-badge)
![Cost](https://img.shields.io/badge/Cost-$26-green?style=for-the-badge)
![Safety](https://img.shields.io/badge/Safety_Rating-9/10-brightgreen?style=for-the-badge)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Demo](#-demo)
- [Features](#-features)
- [Quick Start](#-quick-start)
- [Hardware Components](#-hardware-components)
- [Installation & Setup](#-installation--setup)
- [How It Works](#-how-it-works)
- [Code Structure](#-code-structure)
- [Technical Specifications](#-technical-specifications)
- [Educational Value](#-educational-value)
- [Troubleshooting](#-troubleshooting)
- [Future Improvements](#-future-improvements)
- [Project Credits](#-project-credits)
- [License](#-license)

---

## 🤖 Overview

This project features an autonomous dump truck that uses **three ultrasonic sensors** for 360-degree obstacle detection, enabling the vehicle to navigate its environment intelligently while avoiding collisions. The truck uses **differential steering** for precise turning control and includes **audio feedback** for enhanced user interaction.

**Perfect for:** K-12 STEM education, robotics workshops, engineering demonstrations

---

## 🎥 Demo

**Watch the truck in action:**

[![Arduino Dump Truck Demo](https://img.youtube.com/vi/MdCv9IWyJZ0/maxresdefault.jpg)](https://www.youtube.com/watch?v=MdCv9IWyJZ0)

> Click to watch full video demonstration

**Key Features Demonstrated:**
- ✅ Autonomous obstacle avoidance
- ✅ Smart turning based on sensor data comparison
- ✅ Audio feedback system
- ✅ Real-time navigation decisions

---

## ✨ Features

### 🎯 Triangulated Ultrasonic Sensors
Three HC-SR04 sensors provide complete frontal coverage:
- **Left sensor**: Detects obstacles on the left side
- **Center sensor**: Primary forward-facing collision detection
- **Right sensor**: Detects obstacles on the right side

### 🤖 Autonomous Navigation
Intelligent decision-making based on sensor fusion:
- Automatic obstacle avoidance
- Smart turning logic comparing left vs. right clearance
- Dynamic speed control based on obstacle proximity

### 🔊 Audio Feedback
Horn/buzzer provides audio cues during operation:
- Sounds when backing up
- Alert tones for different maneuvers

### 🎮 Differential Steering
Independent motor control for precise turning:
- Forward/backward movement
- Left/right turning
- Stop functionality

---

## ⚡ Quick Start

**Want to run this right now?**

```bash