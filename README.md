Arduino LED Test:

This repository contains a basic Arduino sketch for testing an LED and jumper wires.

Components:

Arduino Board (Uno, Nano, etc.)

LED

Jumper Wires


Wiring:

Connect the LED's longer leg (positive) to digital pin 11 on the Arduino.
Connect the LED's shorter leg (negative) to ground on the Arduino.

Code: 

int led = 11;

void setup() {
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
}


Usage:

Upload the sketch to your Arduino board.
Observe the LED. If it is lit, the wiring and the LED are working correctly.

Note:
This code will keep the LED turned on indefinitely.
You can modify the code to blink the LED or change its brightness.
This is a simple example to test basic hardware functionality.
