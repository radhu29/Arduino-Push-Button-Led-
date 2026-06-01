Push Button LED using Arduino (Tinkercad)

Project Overview

This project demonstrates how to control an LED using a push button with an Arduino Uno. When the button is pressed, the LED turns ON. When the button is released, the LED turns OFF.

Components Used

Arduino Uno
Breadboard
LED
Push Button
220Ω Resistor (for LED)
10kΩ Resistor (for Button)
Jumper Wires

Circuit Connections

LED Anode (+) → Arduino Pin 13
LED Cathode (-) → 220Ω Resistor → GND
Push Button → Arduino Pin 2
Push Button → 10kΩ Resistor → GND
Arduino 5V and GND connected to Breadboard rails

Working Principle

Arduino continuously reads the state of the push button.
If the button is pressed, Arduino receives a HIGH signal.
The LED connected to Pin 13 turns ON.
When the button is released, the LED turns OFF.
