# latching-power-switch-arduino-circuit
 Overview
This is an Arduino-based latching power switch with an automatic shut-off feature. Pressing the button turns the output ON. After 10 seconds, the system shuts off automatically. Pressing the button again toggles the state.
It’s ideal for small appliances, DIY electronics, or safety systems that need to turn off after a short time without manual intervention.

How It Works
Press the button → Power turns ON
After 10 seconds → Power turns OFF automatically
Press again → Toggles back ON
 Required Components
Arduino Uno
Push button
LED
220Ω resistor (for LED)
n-channel MOSFET
Breadboard
Jumper wires
 Wiring Summary
Push button:
One side connected to GND
The other side connected to Arduino pin D2
MOSFET (nMOS):
Gate connected to Arduino pin D3
Source connected to GND
Drain connected to LED cathode via 220Ω resistor
LED:
Cathode to MOSFET drain
Anode to +5V power
