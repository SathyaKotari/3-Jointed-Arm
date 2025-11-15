Designed and built a 3-Jointed arm in the summer of 2025

3-DOF Robotic Arm – With Arduino


The main goal of the project was to improve my coding skills and learn inverse kinematics for 3 DOF
This project implements a 3-degree-of-freedom robotic arm controller using Arduino and three hobby servos for the shoulder, elbow, and wrist joints
It includes a custom inverse kinematics solver that converts target positions (x, y, z) into servo angles while respecting the travel limits of the servos themselves

**Project Overview:**
- 3-DOF inverse kinematics for shoulder, elbow, and wrist
- Handles both positive and negative Y-coordinates
- Supports custom arm geometry
- Built-in servo physical limit protection
- Automatic NaN and range checking to prevent unsafe movements
- Fully standalone; no external libraries required beyond <Servo.h>, and <math.h>

**Hardware Components Used:**
- Arduino Uno R3
- 3 Servos
- 3D Printed parts
- (Potentiometer for direct servo control)
