# Semi-Autonomous Gas Pipeline Inspection Rover 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<img src="assets/rover_demo.gif" width="800" alt="Rover in action">

## 📌 Project Overview
A semi-autonomous rover for detecting methane leaks in gas pipelines using:
- **Sensors**: MQ-7 gas detectors,
- **Navigation**: Ultrasonic + GPS based object detection 
- **Communication**: Wifi (Esp32) for remote control

**Key Features**:
- ✅ Real-time gas concentration mapping
- ✅ Obstacle avoidance using ultrasonic sensors
- ✅ Web dashboard for monitoring (React.js)
- ✅ 6-hour battery life with solar charging

## 🛠️ Hardware Setup
<img src="assets/wiring_diagram.png" width="400" align="right">

**Components**:
- Chassis: LeWanSeoul 4WD Chasis 
- MCU: Esp32
- Sensors: 
  - Gas detectors (MQ series)
  - Motor Driver (L298N)
  - GPS (NEO-7M)

[View Full BOM](hardware/bom.xlsx) | [CAD Models](hardware/cad/)

## 🖥️ Software Installation
```bash
# Clone repo
git clone https://github.com/yourusername/pipeline-rover.git
