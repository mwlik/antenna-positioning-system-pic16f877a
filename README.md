# Motor Controlling Positioning System

## Overview

This repository contains the code and documentation for a Motor Controlling Positioning System. The project aims to develop a system that enables precise control over the position and movement of motors using microcontroller-based control circuits.

## Features

- Control the direction and speed of a motor using a microcontroller.
- Interface with user inputs to command motor movements.
- Implement Pulse Width Modulation (PWM) for smooth speed control.
- Display relevant information on an LCD screen for user feedback.
- Utilize analog-to-digital conversion for user input handling.
- Incorporate hardware components such as relays and sensors for accurate control.

## Components

- Microcontroller: PIC16F877A
- LCD Display: 16x2 character LCD
- DC Motor: For motor movement simulation
- Relays: To control motor direction
- Potentiometer: For user input of motor speed
- Push Buttons: For user input of motor direction and control

## Getting Started

1. Clone this repository: `git clone https://github.com/mwlik/antenna_positioning_system_pic16f877a.git`
2. Compile and upload the code to your microcontroller.
3. Connect the hardware components as per the circuit diagram (see the PDF).
4. Power on the system and use the interface to control the motor.

## Usage

1. Use the push buttons to select the motor direction (right, left, stop).
2. Adjust the potentiometer to set the desired motor speed.
3. Observe the motor movement and information displayed on the LCD screen.

## Challenges Faced

During the development of this project, several challenges were encountered. These include:
- Creating a custom division algorithm in assembly language.
- Integrating hardware components with precise timing requirements.
- Ensuring reliable motor control and smooth movement transitions.
- Debugging code for accurate sensor readings and user inputs.

## Author of the System

- [M411K](https://github.com/mwlik) And Oussama Awlaqi and a special thanks to prof Alaawami for helping us in trying to realise the project.

## License

This project is licensed under the [MIT License](LICENSE).
