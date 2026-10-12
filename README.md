# Arduino Distance Nightlight

A touchless desk nightlight built with an Arduino and an ultrasonic distance sensor that automatically illuminates an LED when your hand gets close.

## Project Overview

This custom project uses an HC-SR04 ultrasonic sensor to continuously measure the distance of objects near your desk. When an object or your hand comes within a pre-defined threshold distance, the Arduino triggers an LED to turn on, creating a responsive, touch-free nightlight.

## How It Works

1. **Distance Measurement:** The HC-SR04 ultrasonic sensor sends out high-frequency sound waves and measures the echo return time to calculate the distance to nearby objects.
2. **Processing:** The Arduino processes the incoming sensor data through its digital input/output pins.
3. **Triggering Action:** If the measured distance is shorter than the trigger threshold, the Arduino outputs a high signal to light up the LED.

## Components Used

*   **Arduino Uno (or compatible microcontroller)**
*   **HC-SR04 Ultrasonic Sensor**
*   **LED & Current-limiting Resistor**
*   **Breadboard and Jumper Wires**

## Project Image / Schematic

*<img width="778" height="460" alt="image" src="https://github.com/user-attachments/assets/db6d8b7c-d9be-4a20-8c16-413689befd78" />
*
