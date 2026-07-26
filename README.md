# IoT Arduino Projects

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-Uno-00979D?style=for-the-badge&logo=arduino" alt="Arduino Uno">
  <img src="https://img.shields.io/badge/Proteus-Simulation-1f6feb?style=for-the-badge" alt="Proteus">
  <img src="https://img.shields.io/badge/Language-C%2FC%2B%2B-f39c12?style=for-the-badge" alt="Language">
  <img src="https://img.shields.io/badge/Platform-Windows-2ea44f?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Type-Educational-lightgrey?style=for-the-badge" alt="Educational">
</p>

<p align="center">
  Two practical Arduino and Proteus projects for learning embedded systems, sensor interfacing, RFID access control, and simple automation.
</p>

---

## Table of Contents

* [Overview](#overview)
* [Projects](#projects)
* [Features](#features)
* [Repository Structure](#repository-structure)
* [Screenshots](#screenshots)
* [How to Place the Images](#how-to-place-the-images)
* [Requirements](#requirements)
* [How to Run](#how-to-run)
* [Project Details](#project-details)
* [Contributors](#contributors)
* [License](#license)

---

## Overview

This repository contains two educational embedded-systems projects built with **Arduino Uno** and simulated with **Proteus**.

The goal of these projects is to provide clear, beginner-friendly examples of how to work with RFID authentication, LCD display output, temperature sensing, and automatic control logic.

Each project includes:

* source code
* circuit/simulation files
* a project screenshot
* a simple structure that is easy to understand and modify

---

## Projects

### 1) Arduino RFID Based Door Lock

A smart door lock project that checks RFID card access and shows the result on an LCD display.

### 2) UNO LM35 Sensor LCD Motor

A temperature monitoring project that reads data from an LM35 sensor and controls output behavior based on temperature.

---

## Features

* Arduino Uno based
* Proteus simulation included
* Clear and readable code
* LCD output
* RFID access control
* Temperature sensing with LM35
* Suitable for students and beginners
* Easy to study, edit, and expand

---

## Repository Structure

```text
IoT-Projects
│
├── Arduino RFID Based Door Lock
│   ├── Code
│   │   └── Code.ino
│   ├── Circuit.pdsprj
│   ├── Card Numbers.txt
│   └── Arduino RFID Door Security.png
│
└── UNO LM35 Sensor LCD Motor
    ├── Code
    │   └── UNO_LM35_LCD_Motor_1.0.ino
    ├── UNO LM35 Sensor LCD Motor 1.0.pdsprj
    └── UNO_LM35_LCD_Motor_1.0.png
```

---

## Screenshots

### Arduino RFID Based Door Lock

<p align="center">
  <img src="Arduino%20RFID%20Based%20Door%20Lock/Arduino_RFID_Door_Secuirity.png" alt="Arduino RFID Based Door Lock" width="900">
</p>

### UNO LM35 Sensor LCD Motor

<p align="center">
  <img src="UNO%20LM35%20Sensor%20LCD%20Motor/UNO_LM35_LCD_Motor_1.0.png" alt="UNO LM35 Sensor LCD Motor" width="900">
</p>

---

## How to Place the Images

To make the README render correctly on GitHub, place the screenshots exactly inside each project folder and keep the same file names.

Use this exact placement:

```text
Arduino RFID Based Door Lock/Arduino RFID Door Security.png
UNO LM35 Sensor LCD Motor/UNO_LM35_LCD_Motor_1.0.png
```

If you rename a screenshot, update the `src` path in the README too.

For the best look on GitHub:

* use clear, wide screenshots
* keep image names simple
* avoid spaces if possible, or use URL-encoded paths like `%20`
* place each image near the related project section

---

## Requirements

### Hardware

* Arduino Uno
* RFID module
* RFID cards or tags
* LM35 temperature sensor
* LCD display
* LED
* Buzzer
* DC motor
* jumper wires
* breadboard

### Software

* Arduino IDE
* Proteus ISIS
* Windows operating system

---

## How to Run

### 1) Clone the repository

```bash
git clone https://github.com/Mohammadreza-Shahbazi313/IOT-Projects.git
cd REPOSITORY
```

### 2) Open the Arduino code

Open the `.ino` file for the project you want to test in Arduino IDE.

### 3) Open the Proteus simulation

Open the corresponding `.pdsprj` file in Proteus.

### 4) Run the project

* Compile and upload the Arduino code if you are using real hardware
* Or run the Proteus simulation for virtual testing

### 5) Check the output

* RFID project: scan a card and see the access result on the LCD
* LM35 project: change the temperature input and observe the system response

---

## Project Details

### Arduino RFID Based Door Lock

This project implements an RFID-based access control system.

When a valid card is detected:

* access is granted
* the LCD shows a success message
* the system can trigger visual or audio feedback

When an invalid card is detected:

* access is denied
* the LCD shows an error message
* the system alerts the user

### UNO LM35 Sensor LCD Motor

This project reads temperature from an LM35 sensor and displays it on an LCD.

Based on the temperature value:

* the system can activate a motor or other output
* the LCD shows live temperature information
* the project demonstrates simple automation logic

---

## Contributors

This repository was created by:

* [Mohammadreza Shahbazi](https://github.com/Mohammadreza-Shahbazi313)
   [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammadreza-shahbazi-313sh/)
  
* [Abolfazl Ghasemi](https://github.com/abolfazlghasemi83)
 [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abolfazl-ghasemi55/)
---

## License

This repository is intended for educational and learning purposes.

If you want to publish it as open source, you can add a license file such as MIT, Apache 2.0, or GPL based on your preference.
