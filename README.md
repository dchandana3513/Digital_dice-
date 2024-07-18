# Digital_dice-
Digital dice using arduino and 7 segment display.

creating a digital dice using an Arduino microcontroller and a 7-segment display. The digital dice simulates the roll of a traditional six-sided die, displaying the result on a 7-segment display when a button is pressed.

Components

•  Solderless Breadboard: A reusable platform for prototyping electronic circuits without soldering.

•  Arduino Uno: A microcontroller board based on the ATmega328P, used for building digital devices and interactive objects.

•  7-Segment Display Common Anode: A display device with seven LEDs arranged in a pattern to represent numbers, sharing a common positive terminal.

•  Push Button: A momentary switch used to input a signal to the Arduino when pressed.

•  100R Resistor: A 100-ohm resistor used to limit current and protect components like LEDs and the display.

•  Buzzer: An audio signaling device that produces sound when activated by an electrical signal
.
•  Male to Male Jumper Wires: Wires with pins on both ends for making connections between 
components on a breadboard.

•  Battery Clip: A connector used to attach a 9V battery to the circuit.

•  Battery 9V: A power source providing 9 volts of electrical energy for the project.




Assembly Instructions


Mounting the Components:

•  Place the 7-segment display on the breadboard.

•  Insert the push button into the breadboard.

•  Position the Arduino Uno for easy access to its pins.

•  Insert the buzzer into the breadboard.


Wiring:

•  Connect the 7-Segment Display:

•	Connect the common anode of the display to the 5V pin on the Arduino Uno.

•	Connect each segment pin (a-g) of the 7-segment display to digital pins 2 to 8 on the Arduino Uno through 100-ohm resistors to limit the current.

o	Pin a: Digital Pin 2

o	Pin b: Digital Pin 3

o	Pin c: Digital Pin 4

o	Pin d: Digital Pin 5

o	Pin e: Digital Pin 6

o	Pin f: Digital Pin 7

o	Pin g: Digital Pin 8



•  Push Button:

•	One terminal to Digital Pin 9.

•	Other terminal to GND.

•	10k ohm pull-down resistor between Digital Pin 9 and GND.



Buzzer:

•	Positive terminal to Digital Pin 10

•	Negative terminal to GND.



Power connections:


•	GND pins of the Arduino to the ground rail.

•	5V pin of the Arduino to the positive rail.


Power Supply

Connect the Battery:

•	Attach the battery clip to a 9V battery.

•	Connect the positive wire of the battery clip to the VIN pin on the Arduino Uno.

•	Connect the negative wire of the battery clip to one of the GND pins on the Arduino Uno.

 






