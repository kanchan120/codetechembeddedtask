Name : Kanchan nikam
Company : CODTECH IT SOLUTIONS
ID : CT08DS10099Domain 
Domain : Embedded System
Duration : November to December 2024
Overview of the project
project : LED BLINKING WITH ARDUINO
To accomplish the task of blinking an LED with an Arduino, follow these steps:


---

Materials Needed:

1. Arduino board (e.g., Uno, Nano, or Mega)


2. An LED


3. 220-ohm resistor (to limit current)


4. Breadboard


5. Jumper wires


6. USB cable to connect Arduino to your computer




---

Circuit Setup:

1. Connect the longer leg (anode) of the LED to a digital pin (e.g., pin 13) on the Arduino board.


2. Connect the shorter leg (cathode) of the LED to one end of the 220-ohm resistor.


3. Connect the other end of the resistor to the ground (GND) pin of the Arduino.




---

Code for LED Blinking:

Here's a simple Arduino program (sketch) to blink an LED at a 1-second interval:

// Pin where the LED is connected
const int ledPin = 13;

void setup() {
  // Initialize the LED pin as an output
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Turn the LED on
  digitalWrite(ledPin, HIGH);
  delay(1000); // Wait for 1 second

  // Turn the LED off
  digitalWrite(ledPin, LOW);
  delay(1000); // Wait for 1 second
}


---

Steps to Upload the Code:

1. Open the Arduino IDE on your computer.


2. Copy and paste the code above into the IDE.


3. Connect your Arduino board to your computer using the USB cable.


4. Select the appropriate board and port from the Tools menu in the Arduino IDE.


5. Click the Upload button to transfer the code to the Arduino.




---

Expected Output:

The LED will blink on and off with a 1-second interval.

If you want to change the blinking interval, modify the value in the delay() function. For example, delay(500); will create a half-second interval.
Let me know if you need help with any part of this project!
