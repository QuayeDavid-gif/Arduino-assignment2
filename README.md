# Arduino-assignment2
Arduino UNO project: Beeping countdown using tone() and seven segment display 
Arduino Assignment 2 – Beeping Countdown

This repository contains my submission for Assignment 2 in the Programming C++ for Engineers Using Arduino course at Ghana Communication Technology University (GCTU).

Project Overview

This project demonstrates a beeping countdown system using an Arduino Uno, a passive buzzer, and a common-cathode 7-segment display. The display counts down from 9 to 0, producing a short beep at each number. When the countdown reaches 0, the buzzer plays a longer tone to indicate completion.

Features

- Counts down from 9 to 0 on a 7-segment display.
- Produces a short beep for each countdown step.
- Plays a longer completion tone when the countdown finishes.
- Displays countdown progress in the Arduino Serial Monitor.
- Uses arrays, functions, loops, and the "tone()" function for efficient programming.

Hardware Used

- Arduino Uno
- Passive piezo buzzer
- Common-cathode 7-segment display (5161AS)
- 220 Ω resistor
- Breadboard
- Jumper wires
- USB cable

Concepts Demonstrated

- "tone()" and "noTone()" functions
- Passive buzzer operation
- 7-segment display wiring
- Two-dimensional arrays (lookup tables)
- Functions with parameters
- "while" and "for" loops
- Serial Monitor output
- Digital output control

How to Run

1. Connect the passive buzzer to Arduino pin 8.
2. Connect the 7-segment display:
   - a → Pin 2
   - b → Pin 3
   - c → Pin 4
   - d → Pin 5
   - e → Pin 6
   - f → Pin 7
   - g → Pin 9
3. Connect the display COM pin to GND through a 220 Ω resistor.
4. Open the Arduino sketch in the Arduino IDE.
5. Select Arduino Uno under Tools → Board.
6. Select the correct COM port.
7. Upload the sketch to the Arduino.
8. Observe the countdown, buzzer sounds, and Serial Monitor output.

Author

David Quaye
Index Number: 2526400478
BSc Computer Engineering – Group A
Ghana Communication Technology University (GCTU)
