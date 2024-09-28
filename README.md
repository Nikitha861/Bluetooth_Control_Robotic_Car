# Bluetooth_Control_Robotic_Car
Bluetooth controlled car with obstacle avoidance - IOT Project

__Project Overview__

This project involves building a Bluetooth-controlled robotic car that features obstacle detection and avoidance using various electronic components. The system is based on an Arduino Uno board, which serves as the central controller, interfacing with a Bluetooth module for wireless control, and sensors for navigation.

__Key Components__
Arduino Uno Board: The microcontroller that controls all the functionalities of the robotic car, processing inputs from sensors and executing movement commands.
L298N Motor Driver: Controls the speed and direction of the motors attached to the car's wheels, allowing it to move forward, backward, and turn.
HC-SR04 Ultrasonic Sensor: Measures the distance to obstacles ahead of the car, enabling obstacle detection and avoidance.
SG90 Servo Motor: Rotates the ultrasonic sensor to scan the area for obstacles.

__Motors with Wheels__: Provide the movement for the car, controlled by the L298N motor driver.
__Battery Pack__: Powers the Arduino and all connected components, ensuring the car has sufficient energy to operate.
__Jumper Wires__: Used to make all necessary electrical connections between the components.
__Switch__: Powers the entire system on or off.
__How It Works__
__Bluetooth Control__: The car is controlled via a Bluetooth module (HC-05/06), which receives commands from a paired smartphone or Bluetooth-enabled device. Commands include moving forward, backward, turning left or right, and stopping.

__Obstacle Detection and Avoidance__: The HC-SR04 Ultrasonic Sensor mounted on the SG90 Servo Motor scans the front of the car. If an obstacle is detected within a certain range, the car stops, reverses, and attempts to avoid the obstacle by turning.

__Implementation Steps__
__Hardware Setup__:

Connect the L298N motor driver to the motors with wheels and the Arduino Uno board.
Attach the HC-SR04 Ultrasonic Sensor to the servo motor and connect them to the Arduino.
Wire the Bluetooth module to the Arduino’s RX and TX pins.
Use jumper wires to make all the necessary connections between components.
Power the system using the battery pack and include a switch for easy power control.
__Software Setup__:

Upload the provided Arduino code to the Arduino Uno board.
Pair the Bluetooth module with a smartphone or Bluetooth device using a Bluetooth terminal app.
Send control commands to the car and observe its response.
Testing:

Test each command to ensure the car responds correctly.
Place obstacles in front of the car to verify the obstacle detection and avoidance feature.

__Conclusion__
This project is a hands-on way to learn about robotics, electronics, and programming. By integrating the listed components, you can create a functional robotic car that can be controlled remotely and intelligently navigates around obstacles.
