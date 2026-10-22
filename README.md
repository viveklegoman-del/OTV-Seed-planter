# OTV Seed Planting Mission

**ALL TECHNICAL INFO IS IN DESIGN BRIEF PDF ATTACHED TO THIS REPO**

## Overview
**OTV Seed Planter** is an autonomous Omnidirectional Transport Vehicle (OTV) designed to navigate a 4 m $\times$ 2 m arena, avoid obstacles using an ultrasonic sensor, classify soil substrates via a Wi-Fi camera and machine learning, plant seeds, and collect non-plantable substrate samples. Developed collaboratively by a 7 manned student team, every system was designed and integrated to maximize performance and reliability. 

## Key Features
* **Autonomous Navigation:** Utilizes an ArUco marker vision system and a front-mounted ultrasonic distance sensor to detect and bypass obstacles.
* **Substrate Classification:** Employs a Wi-Fi camera trained with a machine learning model to differentiate between plantable and non-plantable substrates.
* **Seed Planting & Collection:** Features a 3D-printed PLA rack-and-pinion claw mechanism to plant seeds and scoop substrate samples.

## Hardware Architecture
* **Microcontroller:** Arduino Mega.
* **Drivetrain:** Omni-wheel configuration driven by four DC motors and two H-bridges.
* **Manipulator Mechanics:** Rack-and-pinion claw assembly powered by three servo motors.
* **Sensors:** One ultrasonic distance sensor and one Wi-Fi camera.

## Power Specifications
* **Power Source:** 12V, 2000mAh NiMH rechargeable battery.
* **Total Power Consumption:** Approximately 4 W.
* **Operating Current:** Total component current draw is approximately 314.2 mA.
