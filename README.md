This project uses an Arduino Nano, a 1-module MAX7219 8×8 LED dot matrix display, and two potentiometers to create an interactive scrolling text display. The system continuously shows the message "Hello World" across the LED matrices while allowing the user to control the scrolling behavior in real time.

The first potentiometer adjusts the scrolling speed, enabling the text to move faster or slower across the display. The second potentiometer controls the scroll direction, allowing the message to scroll either left or right depending on the knob position.

The project uses the MD_Parola and MD_MAX72XX libraries to simplify text animation and display control. Communication between the Arduino Nano and the MAX7219 modules is handled through the SPI interface, providing smooth and responsive text animations.

Features
Scrolls text across a 32×8 LED matrix display.
Adjustable scrolling speed using a potentiometer.
Change text direction (left or right) using a second potentiometer.
Real-time user control without reprogramming the Arduino.
Low-cost and easy-to-build electronics project.
Applications
Electronic message boards
Information displays
Advertising signs
Educational Arduino projects
Interactive LED display demonstrations

This project demonstrates the use of analog inputs, SPI communication, and LED matrix animation, making it an excellent beginner-to-intermediate Arduino project for learning display control and user interaction.
