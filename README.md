# Arduino based motion-sensing light automation system using Proteus

**Aim**

To design and simulate an Arduino-based motion-sensing light automation system using Proteus software by interfacing an Arduino Uno with a PIR (Passive Infrared) motion sensor and an LED, such that the light automatically turns ON when motion is detected and turns OFF after a specified delay when no motion is present.

**Apparatus Required**
S.No.	Component/Software	Specification	Quantity

1	Arduino Uno	ATmega328P	1
2	PIR Motion Sensor	HC-SR501 (Proteus Library)	1
3	LED	5 mm	1
4	Resistor	220 Ω	1
5	Breadboard (Virtual)	Proteus Component	1
6	Connecting Wires	Virtual	As required
7	Proteus Design Suite	Version 8 or later	1
8	Arduino IDE	For compiling Arduino code	1
9	HEX File	Generated from Arduino IDE	1

**Procedure**
Open Proteus Design Suite and create a new project.
Place the following components on the workspace:
Arduino Uno
PIR Motion Sensor
LED
220 Ω resistor
Connect the PIR sensor output to Digital Pin D2 of the Arduino.
Connect the LED through the 220 Ω resistor to Digital Pin D13.
Provide proper 5 V and GND connections to all components.
Write the Arduino program in the Arduino IDE to monitor the PIR sensor output and control the LED.
Compile the Arduino sketch and generate the HEX file.
Load the HEX file into the Arduino Uno in Proteus.
Run the simulation.
Change the PIR sensor state to simulate motion detection.
Observe that:
When motion is detected, the LED turns ON.
When no motion is detected, the LED turns OFF after the programmed delay.
Verify the operation by repeating the simulation several times.

**Circuit Diagram**

<img width="1917" height="960" alt="Screenshot 2026-08-04 141801" src="https://github.com/user-attachments/assets/ea6567d8-f02c-403f-a0d8-d72cd09b9e13" />






**Output**

<img width="1917" height="1078" alt="Screenshot 2026-08-04 141831" src="https://github.com/user-attachments/assets/460c3df4-540c-40ca-a612-7c85d5491caf" />





**Result**

The Arduino-based motion-sensing light automation system was successfully designed and simulated in Proteus. The Arduino accurately detected motion signals from the PIR sensor and automatically controlled the LED. The system successfully demonstrated automatic lighting control, making it suitable for applications such as smart homes, corridors, staircases, offices, parking areas, and energy-efficient lighting systems.
