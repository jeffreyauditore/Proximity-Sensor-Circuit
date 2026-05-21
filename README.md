![Project Image](Copy%20of%20Proximity%20Sensor%20Circuit%20and%20Code.png)
# Proximity Sensor Circuit and Code

Simple Arduino project using the HC-SR04 ultrasonic sensor to detect nearby objects and turn on a light when the distance is below a specified value.

## Components
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- LED / Lamp
- Breadboard
- Resistor
- Wires

## Features
- Measures distance using ultrasonic waves
- Displays distance in Serial Monitor
- Turns on light when object is close
- Real-time proximity detection

## Circuit
The HC-SR04 sensor is connected to Arduino Uno:
- VCC → 5V
- GND → GND
- TRIG → D3
- ECHO → D2

LED output:
- LED → D7

## How It Works
1. Sensor sends ultrasonic pulse
2. Measures return time
3. Calculates distance
4. If distance < 80 cm:
   - LED turns ON
5. Otherwise:
   - LED turns OFF

## Code
Written in Arduino C++.

## Simulation
Created in Tinkercad.

## Author
Vasyl
