# Servo-Project
This project moves 2 servo opposite each other at the same time
--
📝 Project Title:

Controlling Two Opposite Moving Servo Motors Using Arduino

📄 Description:
This project demonstrates how to control two SG90 servo motors with an Arduino Uno board. The servos move in opposite directions: while the first servo rotates from 0° to 180°, the second rotates from 180° back to 0°. This creates a synchronized, dynamic, and opposing motion.

The program utilizes the Arduino Servo.h library and employs for loops to smoothly control servo angles.

🎯 Project Objectives:
Learn how to connect and control servo motors with Arduino.
Implement smooth servo movement using loops.
Apply logic to make two servos move in opposite directions.

⚙️ Components Used:
1 × Arduino Uno
2 × SG90 Servo Motors
Jumper wires
5V Power source or USB power

🧠 How It Works:
The Arduino attaches each servo to pins D9 and D10.
The first servo gradually moves from 0° to 180°.
Simultaneously, the second servo moves from 180° down to 0°.
Then the movement reverses and repeats continuously.

💡 Possible Applications:
Robotic arms
Automated small doors
Mechanisms requiring opposing movements
