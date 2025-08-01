Project 1: Touch-Based LED Control System
Title: Capacitive Touch Sensor-Based Smart LED Interface Using Arduino UNO
Components Utilized:
Arduino UNO Board
TTP223 Capacitive Touch Sensor
LED (Red/White)
1kΩ Resistor (for current-limiting)
USB Data Cable (for programming and power)
Jumper Wires
PCB with soldered components and connection points

Operational Logic and Control Flow
When a user touches the surface of the TTP223 sensor, a HIGH logic signal (digital 1) is sent to the Arduino.
The Arduino reads this input and triggers the LED to turn ON.
Upon release (no touch), the sensor sends a LOW signal (digital 0), and the LED is turned OFF.
The system can be extended to control other loads like relays or small appliances.

Logic Table:
Touch Sensor Input
Arduino Output
LED State
HIGH (Touched)
Digital HIGH
ON
LOW (Not Touched)
Digital LOW
OFF

Real-Life Applications
Home Automation Systems: Capacitive switches for lights, fans, and appliances without mechanical wear.
Public Utilities: Touch-based access panels in hygiene-sensitive environments (e.g., hospitals, food processing areas).
Smart Furniture: Nightstands, desk lamps, or wall panels with touch-enabled lighting.
Accessible Interfaces: For individuals with limited motor skills, eliminating the need for physical force.


Gas Detection Integration (Safety Monitoring)
In parallel to the control circuit, the gas sensor module was integrated for continuous air quality monitoring:
Digital Threshold Triggering: When gas concentration crosses a set level, Arduino triggers an alert (e.g., buzzer or LED)
Analog Monitoring (optional): Sensor output can be mapped to an analog pin for real-time ppm-based monitoring on an LCD or serial monitor

Safety and Automation Applications
Kitchen Safety Systems: Automatic fan or alarm activation on LPG leakage detection.
Industrial Plants: Monitoring flammable gas build-up to prevent fire hazards.
Smart Buildings: Automated ventilation control based on air quality.
Air Purifiers: Trigger filtering or ventilation based on pollutant concentration.

Conclusion
The project successfully demonstrated a multifunctional smart system integrating user interaction (touch-based control) and environmental monitoring (gas detection). The design and fabrication of a custom PCB, including SMD and through-hole soldering, added hands-on experience in hardware development. The acid etching technique for PCB manufacturing further provided exposure to real-world prototyping methods. This modular setup can serve as a core framework for developing smart automation systems in both domestic and industrial environment

