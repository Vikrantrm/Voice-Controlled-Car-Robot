Voice-Controlled Car Robot

An Arduino-based robotic vehicle designed to operate hands-free using smartphone voice commands. The system leverages Bluetooth communication to provide an accessible and intuitive mobility solution for individuals with physical disabilities.
Project Status: Active / Prototype
Tech Stack: Arduino, Embedded C/C++, Bluetooth (HC-05), Android

Problem Statement
Many amputees and individuals with physical disabilities depend heavily on others for mobility and daily activities. Although robotic systems controlled by joysticks or touch-based interfaces exist, these methods can still be challenging or impractical for users with limited motor control.
There is a strong need for a hands-free, voice-driven mobility solution that is simple, affordable, and intuitive to operate.

Proposed Solution
The Voice-Controlled Car Robot enables users to control a robotic vehicle using spoken commands through a smartphone application. By combining speech recognition with embedded systems, the project eliminates the need for physical interaction.

System Workflow
Input:
The user speaks commands such as “move forward,” “turn left,” or “stop” into a custom Android application.
Processing:
The application converts voice input into text and transmits the command wirelessly to the robot using a Bluetooth (HC-05) module.
Execution:
An Arduino UNO receives the command, processes the text string, and controls the motors through an L298N motor driver to perform the desired movement.

Key Components
Microcontroller: Arduino UNO (ATmega328P)
Communication Module: HC-05 Bluetooth Module (UART protocol)
Motor Driver: L298N Dual H-Bridge
Drive System: 100 RPM DC Motors
Power Supply: 12V DC source
Development Environment: Arduino IDE (C/C++)

Applications & Target Audience
Assistive Technology
Can be adapted for wheelchairs or mobility aids to enhance independence for individuals with disabilities.
Service Industry
Voice-controlled service robots for hotels, hospitals, or restaurants, creating inclusive job opportunities for differently-abled individuals.
Hazardous Environments
Future versions may be deployed in mining, defense, or disaster zones where human access is risky.
Education & Hobbyists
A foundational project for learning robotics, IoT, Bluetooth communication, and speech recognition integration.

Future Enhancements
Integration of cameras and environmental sensors (e.g., gas detection) for autonomous monitoring
Addition of solar panels to improve energy efficiency
Expansion into smart home and IoT-based automation systems
Improved natural language processing for more flexible voice commands

Team Members

R.M.Vikrant 

S.Sudharshanan

V.A.Niranjan Balaji

Date Uploaded: December 2025
Date of Project: January 2025
License: Open Source

Thank You
