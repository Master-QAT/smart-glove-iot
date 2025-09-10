# smart-glove-iot
Prototype of a Smart Glove using potentiometers and servo motors as placeholders for flex sensors and actuators. Built with ESP32/Arduino for assistive technology and gesture control research.

Smart Glove

 Short Description

This project is a prototype of a Smart Glove that demonstrates how finger movements can be captured and translated into mechanical motion. In this testing phase, potentiometers are used as placeholders for flex sensors, while servo motors simulate the glove’s actuation. The project is designed as a foundation for future wearable assistive technology.

 Features

Simulates finger bending using potentiometers (as flex sensor placeholders).

Controls servo motors to mimic finger movement.

Outputs real-time angle readings via Serial Monitor.

Provides an expandable base for gesture-controlled robotics and assistive devices.

 Components Used
Hardware

Arduino board (e.g., Uno, Nano)

Potentiometers (acting as flex sensor placeholders)

Servo motors (acting as actuator placeholders)

Jumper wires & breadboard

Software

Arduino IDE (for coding and uploading sketches)

Servo.h library (for controlling servo motors)

⚠️ Note: Potentiometers and servos are placeholders in this prototype. In the full smart glove, they would be replaced with flex sensors and mechanical actuators.

 How It Works

Each potentiometer represents a finger’s bending motion.

The Arduino reads analog values from the potentiometers.

The values are mapped to angles for servo motors.

The servo motors move to reflect finger bending.

Serial Monitor displays real-time angle readings for debugging.

This setup demonstrates the control concept before replacing placeholders with actual sensors and actuators in the glove.

👤 Author

Master QAT – Student | AI & Robotics Enthusiast | Future Robotics Engineer 🚀
