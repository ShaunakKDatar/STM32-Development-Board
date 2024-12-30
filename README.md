# STM32F1038TX Development Board

## Overview
This STM32F1038TX development board is designed for embedded system developers and hobbyists. It features essential peripherals and interfaces for rapid prototyping and testing. The board is powered by an AMS1117 voltage regulator, ensuring a stable 3.3V supply from USB input.

## Features
- **Microcontroller:** STM32F1038TX (ARM Cortex-M3)
- **Clock:** 16MHz External Crystal Oscillator
- **Voltage Regulator:** AMS1117 (USB to 3.3V conversion)
- **Connectors:**
   - UART
   - SWD (Serial Wire Debug)
   - I2C
- **Switches:**
   - User SPDT Switch
   - NRST (Reset) Switch
   - BOOT0 Switch
- **User LED:** 1 programmable user LED

## Pin Configuration
- **UART Pins:** TX (PA9), RX (PA10)
- **I2C Pins:** SDA (PB7), SCL (PB6)
- **SWD Pins:** SWCLK (PA14), SWDIO (PA13)
- **User LED:** PA5
- **SPDT Switch:** PA0
- **NRST Switch:** NRST Pin
- **BOOT0 Switch:** BOOT0 Pin

## Power Supply
- **Input Voltage:** 5V via USB
- **Regulated Voltage:** 3.3V via AMS1117

## Programming and Debugging
1. Use an SWD programmer (e.g., ST-Link V2) for flashing firmware.
2. Ensure BOOT0 is set to 0 for normal operation, 1 for DFU/bootloader mode.
3. Use UART for serial communication.

## Getting Started
1. Connect the board to your computer via USB.
2. Flash firmware using SWD.
3. Use UART for debugging and monitoring.
4. Toggle the User LED and interact with the SPDT switch.

## Safety Precautions
- Ensure correct power supply voltage.
- Avoid short circuits on the board.
- Handle components with care.

## Schematics
<img width="832" alt="Screenshot 2024-12-30 at 3 51 30 PM" src="https://github.com/user-attachments/assets/82357a1a-a06c-47fd-ab5a-4c7681131865" />


## PCB Routing
<img width="832" alt="Screenshot 2024-12-30 at 3 52 11 PM" src="https://github.com/user-attachments/assets/32d763b7-f961-4a5c-9756-34d47c28c823" />
<img width="832" alt="Screenshot 2024-12-30 at 3 52 20 PM" src="https://github.com/user-attachments/assets/65bbb700-f78e-46c7-bfe0-e13bd799b4f1" />



## 3D Model
<img width="780" alt="Screenshot 2024-12-30 at 3 52 34 PM" src="https://github.com/user-attachments/assets/512e9c35-3c09-40c5-94fb-0a0e3fe0752b" />


## Resources
- [STM32F103 Reference Manual](https://www.st.com/resource/en/reference_manual/cd00171190.pdf)
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)

## License
This project is open-source under the MIT License.

