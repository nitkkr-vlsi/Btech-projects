# Line Follower Robot

## Overview
An Arduino-based robot that follows a path using three IR sensors and conditional motor-control logic.

## Hardware
- Arduino-compatible microcontroller
- Three IR sensors (left, middle, right)
- DC motors and motor driver
- Robot chassis and power supply

## Pin Configuration

| Component | Arduino Pins |
|---|---|
| Left motor control | 10, 9 |
| Right motor control | 5, 3 |
| Left IR sensor | 12 |
| Middle IR sensor | 7 |
| Right IR sensor | 2 |

## Features
- Three-sensor line detection
- Forward movement and directional turns
- Conditional logic for intersections and dead ends
- PWM-based motor control

## Technologies
Arduino C/C++, digital input/output, PWM motor control.
