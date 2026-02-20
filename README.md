# Autonomous Mapping Robot with RF Remote Control

16×16 grid-based autonomous mapping robot built on Arduino Nano 33 BLE Sense.  
Supports manual control, autonomous exploration, and return-to-home navigation.

Full implementation details are in the attached PDF documentation.

---

## My Contribution (Jongchan Park)

Primarily responsible for the system software implementation.

- Implemented the core control logic in C++ (Arduino Framework)
- Designed the 16×16 occupancy grid mapping and autonomous navigation logic
- Developed return-to-home algorithm and movement calibration
- Integrated IMU-based collision detection and RF remote control handling

---

## Tech Stack

### Language
- C++ (Arduino Framework)

### Hardware Platform
- Arduino Nano 33 BLE Sense (ARM Cortex-M4)
- 4WD DC Motor System
- L293D H-Bridge (Direct PWM control)

### Sensors
- HC-SR04 Ultrasonic Sensor
- LSM9DS1 IMU
- APDS9960 Light Sensor

### Control System
- 433MHz RF Remote (GPIO-based digital input)
- Servo-based directional scanning

---

## System Features
- 16×16 Occupancy Grid Mapping
- Real-time ASCII Map Rendering (Serial Monitor)
- IMU-based Collision Detection
- Compass Calibration + Heading Verification
- Grid-based Return-to-Home Logic
- Multi-voltage domain power design (18V → 5V → 3.3V)
