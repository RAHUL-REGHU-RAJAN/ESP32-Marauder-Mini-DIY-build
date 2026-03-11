# ESP32-Marauder-Mini-DIY-build
<p align="center"><img alt="Marauder logo" src="https://github.com/RAHUL-REGHU-RAJAN/ESP32-Marauder-Mini-DIY-build/blob/main/Assets/marauder_logo.png?raw=true" width="300"></p>

## Overview
This project documents the design, hardware integration, and testing of a DIY ESP32 Marauder Mini, a compact portable device used for wireless security analysis and educational cybersecurity research.

The system is built around the ESP32 DevKit microcontroller and integrates multiple hardware modules including a TFT display, GPS receiver, SD card logging interface, and joystick navigation module.
The device runs the ESP32 Marauder Mini firmware developed by JustCallMeKoko, providing a menu-driven interface for performing wireless reconnaissance and security testing operations.

This repository focuses on the understanding wireless network security, hardware implementation, system integration, debugging process, and testing methodology used to create the final working device.

# Hardware Components
* **ESP32 DevKit**: 	Main microcontroller
* **1.44" TFT Display**: 	User interface
* **NEO-6M GPS Module**:	Location data for wardriving
* **SD Card Module**: 	Data logging
* **5-Way Switch Module**: 	Menu navigation
* **Lithium Battery + Boost Converter**: 	Portable power system

# Hardware Architecture
* **[GPIO Connection](Assets/gpio_pins.md)**: ESp32 GPIO pins and connections.
* **[Orginial Schematics](Assets/justcallmekeko_schematics.png)** by [justcallmekeko](https://github.com/justcallmekoko): The Original Schematics of ESP32 Marauder.
* **[Wiring Diagram](Assets/wiring.jpg)**: Wiring and Battery Connection Diagram.

## Firmware
The device runs the ESP32 Marauder Mini firmware, an open-source wireless security research platform.

Firmware by:
JustCallMeKoko

Official Repository:
https://github.com/justcallmekoko/ESP32Marauder

This project does not modify or redistribute the firmware, and only documents the hardware build and integration process.

# Documentation
Full technical report available here: [DIY MARAUDER MINI - RAHUL REGHU RAJAN ](https://github.com/RAHUL-REGHU-RAJAN/ESP32-Marauder-Mini-DIY-build/blob/main/Documents/DIY%20MARAUDER%20MINI%20-%20RAHUL%20REGHU%20RAJAN.pdf)

The report includes:
* System architecture
* Implementation details
* Testing methodology
* Challenges encountered
* Learning outcomes

# Ethical Use Notice

This device is intended strictly for:
* Cybersecurity education
* Wireless security research
* Authorized penetration testing environments

Unauthorized use against networks or devices without permission is strongly discouraged.

# Attribution
This project uses the ESP32 Marauder firmware created by [JustCallMeKeko.](https://github.com/justcallmekoko)

Full credit for the firmware, features, and original project concept belongs to the original developer and contributors.

This repository documents only the hardware implementation, understanding wireless network security, offensive and defensive learning process.

# Author
**Rahul Reghu Rajan** - Penetration Testing | Linux & Tools | VAPT | Red Team Concepts.

Email: rahul.rajanempire@gmail.com

Portfolio: <a href="https://www.rahulhub.vercel.app">rahulhub.vercel.app</a>
