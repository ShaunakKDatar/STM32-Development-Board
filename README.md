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

## Resources
- [STM32F103 Reference Manual](https://www.st.com/resource/en/reference_manual/cd00171190.pdf)
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)

## License
This project is open-source under the MIT License.

