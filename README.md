# Arduino Car with Ultrasonic Sensor ReadMe

This repository contains the Arduino code for a simple car project equipped with an ultrasonic sensor. The project utilizes various components, including a car chassis, DC gear motors, wheels, an ultrasonic sensor, and other electronic elements. Below is a brief guide to help you understand and implement this code for your Arduino-based car project.


![arduinocar1](https://github.com/ingli0/arduinoCarObstacleAvoidance/assets/76855285/cdd4e59e-0f2a-444f-a0b0-fca9349c2521)


![arduinocar2](https://github.com/ingli0/arduinoCarObstacleAvoidance/assets/76855285/8ddef80e-a947-47ea-84db-d77b928aa13d)



![arduinocar3](https://github.com/ingli0/arduinoCarObstacleAvoidance/assets/76855285/cadf7dc4-8350-4588-be44-93b4a9059492)
## Hardware Requirements

Ensure you have the following components before using this code:

1. Car chassis
2. Car wheels (2)
3. DC Gear Motors (2) - 48:1 ratio (alternatively, 120:1 ratio)
4. 20 line gun code disk (2)
5. Fasteners (high-intensity black acrylic) - 4 pieces
6. Caster - 1 piece
7. Four battery box - 1 piece
8. Quality Rocker Switch - 1 piece
9. Several screw nuts
10. V5 shield - 1 piece
11. Arduino UNO R3 - 1 piece
12. SG90 Servo Motor - 1 piece
13. L298N Motor Driver - 1 piece

## Wiring Instructions

Follow the assembly drawing to connect the components correctly. Make sure to double-check your wiring to prevent any issues.


## Arduino Code Overview

The provided Arduino code is responsible for controlling the car's movements based on the readings from the ultrasonic sensor. Here's a brief overview of the code structure:

- **Motor Control Functions:** The `go` function controls the movement of the left and right motors, allowing the car to move forward, backward, or stop.
- **Motor Testing:** The `testMotors` function tests the movement of both motors at various speeds.
- **Ultrasonic Sensor Reading:** The `readDistance` and `readNextDistance` functions handle reading the distance from the ultrasonic sensor at different angles using a servo motor.
- **Setup:** Initializes serial communication, sets up pins, attaches the servo motor, and positions the sensor angle for the initial reading.
- **Loop:** Continuously reads distance values from the ultrasonic sensor and adjusts the car's movement based on the readings.


## Getting Started

1. Connect all the hardware components as per the assembly drawing.
2. Upload the provided Arduino code to your Arduino UNO R3.
3. Power up the system and observe how the car behaves based on the ultrasonic sensor readings.


## Troubleshooting

If the car's behavior is unexpected or erratic, double-check your wiring and ensure all components are properly connected. Adjustments may be needed based on the specific characteristics of your hardware setup.

Feel free to experiment with different sensor angles, motor speeds, and distances to optimize the performance of your Arduino car.

For any issues or questions, please refer to the [Issues](https://github.com/ingli0/arduinoCarObstacleAvoidance/issues) section of this repository.

Happy tinkering!
