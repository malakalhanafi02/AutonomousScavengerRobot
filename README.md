# 🤖 Autonomous Scavenger Robot

## Project Overview
The Autonomous Scavenger Robot is designed to navigate an environment, collect valuable objects (gems), sort them by color, and return to a home base. This project was developed as part of the MSE2202 course at Western University. The robot uses a combination of sensors, microcontrollers, and custom algorithms to achieve its tasks.

## ✍️ Authors

Malak Al-Hanafi, Shayla Diep, Nathan Eng, Ben Prentice


# Introduction

## Problem Statement
Robotic systems are essential for collecting objects in hazardous environments. The objective of this project is to design an autonomous mechatronic system capable of collecting valuable objects, storing them securely, and depositing them at a base station.


# Design and Implementation

## 🔑 Key Design Decisions 
1. Drive System: Uses motor controllers and encoders for precise movement.
2. Sorting System: Utilizes a color sensor and servos to sort valuable gems.
3. Pick-Up System: A claw mechanism collects and deposits gems.

## ⚠️ Design Constraints and Requirements
1. Compact and lightweight
2. Object sorting by color
3. Self-powered with a 2-minute operation time
4. Collision avoidance


## Microcontroller and Sensors
- Microcontroller: Custom-made MSEduino (ESP32-based)
- Sensors:
    1. Color sensor (Adafruit TCS34725)
    2. Ultrasonic sensor for distance measurement
    3. IR sensor for localization
    4. Encoders for motor feedback

# Robot Workflow diagram

<img width="887" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/096259cc-fb8b-4cb6-bc92-b63557a8f2cc">

# 🫳 The Claw 
The claw design uses high-grade PLA/PLA+ for its lightweight and durable properties. The claw is designed to minimize the load on the servo while maintaining effective gem collection. It includes a HS-322HD servo motor for robust operation, side extensions to direct gems, and a rotating flap powered by a DC motor to sweep gems into the claw. These features enhance the claw's performance, increasing the pick-up rate and reducing the risk of operational failure due to overloading.

<img width="296" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/97bb5d70-d515-49ed-aaf6-6522ad384827">
<img width="247" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/ca0f54b4-6ec0-4554-a685-359fd601c009">


# 🛞The wheels 
The wheel design uses elastic bands for traction. This choice provided better grip and ensured even movement, significantly improving the robot's navigation and performance.

<img width="383" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/ae8d89ab-f5d5-4d3d-8098-df44c179495d">

# 🖥️ Full Assembly CAD Model

<img width="980" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/2f8f975c-a62d-4c7e-92e9-5c39ef0ac480">

# ⚡️Circuit Diagrams:

1. Drive System:

<img width="912" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/82729945-5b42-4c6c-8030-ff67a4cea443">


2. Sorting Base:

<img width="955" alt="image" src="https://github.com/malakalhanafi02/AutonomousScavengerRobot/assets/122760944/df7065d2-8155-492c-9a20-2f38861b2e52">












