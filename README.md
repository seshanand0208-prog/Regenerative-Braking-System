ESP32 Regenerative Braking System

An ESP32-based regenerative braking concept prototype that demonstrates DC motor control, electrical braking, and real-time system monitoring using an L298N motor driver, 16×2 I2C LCD, and LED indicator.

📌 Overview

Regenerative braking is an important technology in electric and hybrid vehicles. During braking, the motor can operate as a generator and convert some of the vehicle's kinetic energy into electrical energy.

This project demonstrates the control and braking concept using a DC motor. The ESP32 controls the motor through an L298N driver and automatically switches between acceleration, running, braking, and stopped modes.

Note: The current prototype demonstrates electrical/dynamic braking. It does not actually recover and store energy in a battery or supercapacitor.

✨ Features
ESP32-based motor control
DC motor with L298N driver
PWM speed control
Automatic acceleration and running
Electrical/dynamic braking
16×2 I2C LCD status display
LED braking indicator
Automatic operating cycle
Arduino board used as 5 V control power source
🧰 Components
ESP32 Development Board
Arduino Board
L298N Motor Driver
DC Motor
16×2 I2C LCD
LED
220 Ω resistor
DC motor power supply
Jumper wires
