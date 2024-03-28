# PID Controlled Line Follower

## Overview
This project focuses on the development and implementation of a PID (Proportional-Integral-Derivative) controlled line follower robot. Utilizing PID control algorithms, this robot can precisely follow a predefined path marked on the surface with minimal deviation. The PID controller adjusts the motor speeds based on the deviation from the path, ensuring smooth and accurate navigation.

## Features
High Precision Tracking: Leverages a PID control loop for precise maneuvering and path tracking.
Customizable Parameters: Offers adjustable PID coefficients for optimized performance under various conditions.
Real-Time Adjustments: Implements real-time feedback to continuously correct the course.
Extensive Documentation: Includes detailed setup guides, wiring diagrams, and code comments.

## Components
Microcontroller (e.g., Arduino, Raspberry Pi)
IR Sensors / Color Sensors for line detection
DC Motors with encoders for precise movement control
Motor Driver (e.g., L298N, H-bridge)
Power Source (battery pack)
Chassis and Wheels
Bluetooth module for remote monitoring

## Setup & Installation
Assemble Hardware: Connect the sensors, motors, and motor driver to the microcontroller according to the wiring diagram provided in the docs directory.
Software Setup: Download and install the required libraries from the lib directory. Load the provided code into your microcontroller.
Calibration: Follow the calibration procedure outlined in the calibration directory to adjust the sensor sensitivity and PID coefficients.
Testing: Place the robot on a track and power it up. Adjust the PID coefficients as needed to improve path tracking.

## Usage
To start the line follower, ensure the track is properly laid out with clear contrasting colors. Power on the robot and place it at the start of the track. The robot will begin to follow the line, adjusting its speed and direction using the PID algorithm.

## Demo video
https://drive.google.com/file/d/1a7WgN_vODmALlGC3BkMuvdqwfmZITlDh/view?usp=drive_link
