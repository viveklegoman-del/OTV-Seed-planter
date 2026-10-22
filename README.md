# OTV Seed Planting Mission

##ALL TECHNICAL INFO IS IN DESIGN BRIEF PDF ATTACHED TO THIS REPO

## Overview
**OTV Seed Planter** is an autonomous Omnidirectional Transport Vehicle (OTV) designed to navigate a 4 m $\times$ 2 m arena[cite: 7, 8], avoid obstacles using an ultrasonic sensor[cite: 8, 13], classify soil substrates via a Wi-Fi camera and machine learning[cite: 4, 13], plant seeds[cite: 4], and collect non-plantable substrate samples[cite: 4]. Developed collaboratively by a 7 manned student team, every system was designed and integrated to maximize performance and reliability. 

## Key Features
* **Autonomous Navigation:** Utilizes an ArUco marker vision system and a front-mounted ultrasonic distance sensor to detect and bypass obstacles[cite: 7, 8, 13].
* **Substrate Classification:** Employs a Wi-Fi camera trained with a machine learning model to differentiate between plantable and non-plantable substrates[cite: 4, 13].
* **Seed Planting & Collection:** Features a 3D-printed PLA rack-and-pinion claw mechanism to plant seeds and scoop substrate samples[cite: 3, 4, 13].

## Hardware Architecture
* **Microcontroller:** Arduino Mega[cite: 13].
* **Drivetrain:** Omni-wheel configuration driven by four DC motors and two H-bridges[cite: 9, 13].
* **Manipulator Mechanics:** Rack-and-pinion claw assembly powered by three servo motors[cite: 3, 4, 13].
* **Sensors:** One ultrasonic distance sensor and one Wi-Fi camera[cite: 4, 8, 13].

## Power Specifications
* **Power Source:** 12V, 2000mAh NiMH rechargeable battery[cite: 13].
* **Total Power Consumption:** Approximately 4.07 W[cite: 14].
* **Operating Current:** Total component current draw is approximately 314.2 mA[cite: 14].
