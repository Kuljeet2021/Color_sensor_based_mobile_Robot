Color Sensor Based Mobile Robot
This project involves creating a mobile robot that utilizes a color sensor to detect different colors and responds accordingly by moving and activating LEDs. The robot is programmed using Arduino.

Description
The robot is equipped with a color sensor capable of detecting red, green, and blue colors. Based on the intensity of each color detected, the robot performs specific actions:

Red Color Detection: If the intensity of red is the lowest among the detected colors and falls below a certain threshold, the robot stops and turns on a red LED.
Blue Color Detection: If the intensity of blue is the lowest among the detected colors, the robot moves forward and turns on a blue LED.
Green Color Detection: If the intensity of green is the lowest among the detected colors, the robot moves backward and turns on a green LED.
The project also includes LED indicators to visually display the detected colors.

Hardware Requirements
Arduino board
Color sensor module
LED modules (red, green, blue)
Motor driver module (for robot movement)
DC motors and wheels
Setup Instructions
Connect the color sensor module to the Arduino board according to the pin configurations specified in the code.
Connect the LED modules to the Arduino board.
Connect the motor driver module to control the robot's movement.
Upload the provided Arduino code to the Arduino board.
Power up the Arduino board and observe the robot's behavior when exposed to different colors.
Code Explanation
The Arduino code consists of setup and loop functions:

Setup Function: Initializes the necessary pins and sets the initial conditions.
Loop Function: Continuously reads the intensity of red, green, and blue colors detected by the sensor. Based on the detected colors, the robot performs specific actions as described above.
Contributing
Contributions to improve and expand this project are welcome! Please feel free to fork this repository, make changes, and submit pull requests.
