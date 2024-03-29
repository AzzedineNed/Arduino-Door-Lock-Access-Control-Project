# Arduino Door Lock Access Control Project

## Overview
This Arduino project implements a simple door lock access control system using an RFID module. The system allows access based on the scanned RFID card, providing visual and audible feedback to the user through LEDs and a buzzer. An LCD display communicates with the user and displays relevant information.

## Components Used
- Arduino Board
- MFRC522 RFID Module
- 16x2 LCD with I2C interface
- Relay for Lock Control
- LEDs (Green and Red)
- Buzzer

![Components](https://github.com/AzzedineNed/Arduino-Door-Lock-Access-Control-Project/blob/main/components.jpg)

## Dependencies
- [MFRC522 Library](https://github.com/miguelbalboa/rfid) for RFID module communication.

## Installation
1. Download and install the required libraries.
2. Connect the components according to the circuit diagram.

## Circuit Diagram
 
![Circuit Diagram](https://github.com/AzzedineNed/Arduino-Door-Lock-Access-Control-Project/blob/main/circuitPNG.PNG)

## Setup
1. Upload the provided Arduino script to your Arduino board.
2. Verify and upload the script using the Arduino IDE.

## Usage
1. Power up the system.
2. Scan a valid RFID card.
3. Access will be granted or denied based on the card's access code.
4. Visual and audible feedback will be provided.

## Customization
- Modify the `master` array in the script to set your desired access code.
- Adjust pin configurations based on your hardware setup.

## Contributing
Feel free to contribute to the project by creating issues or pull requests.
