# Arduino Distance Nightlight

A simple desk nightlight built using an Arduino and an ultrasonic distance sensor that automatically turns on an LED when your hand gets close.

## Project Overview

This project uses an ultrasonic sensor to measure the distance of objects (like a hand) placed near the sensor. When an object comes within a specified threshold distance, the Arduino triggers an LED to light up, functioning as a touchless desk nightlight.

## How It Works

1. **Distance Measurement:** The HC-SR04 ultrasonic sensor emits high-frequency sound waves and measures how long they take to bounce back, calculating the distance to the nearest object.
2. **Processing:** The Arduino reads the sensor data via its digital pins.
3. **Action:** If the distance is below the set threshold, the Arduino sends a signal to turn on the LED connected to the circuit.

## Project Image

![Arduino Distance Nightlight Circuit Design](https://halflife.hackclub.com/projects/cmurt3c5u016l01smyyk3z4mw)
*(Replace or link your schematic/photo here if necessary)*

## Components Used

*   **Arduino Uno (R3 CH340)** (Main Controller)
*   **HC-SR04 Ultrasonic Sensor Module** (Distance Measurement)
*   **Breadboard, Jumper Wires, Resistors, and LEDs**
