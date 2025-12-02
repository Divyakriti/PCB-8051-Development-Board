# PCB-8051-Development-Board
A practice PCB project that integrates USB-UART, USB-RS232, and an 8051 microcontroller system for learning and experimenting with serial communication, power regulation, and classic interface standards.

# Key Functional Blocks
## 1. Power Supply Section
- DC barrel jack for external power input
- 7805 voltage regulator generates stable 5V
- Filter capacitors for smoothing
- Power indicator LED
  
## 2. USB–UART Section
- Micro USB port connected to FT232
- Converts USB signals ↔ TTL serial (0–5V)
- Used for direct communication with the 8051 microcontroller
- Ideal for debugging, programming, and serial monitoring
- 
## 3. USB–RS232 Section
- DB9 connector for classic COM-port devices
- MAX232 IC converts TTL ↔ RS-232 levels (±12V)
- Allows communication with legacy PCs, machines, and industrial hardware

## 4. 8051 Microcontroller Section
- 40-pin 8051 MCU
- External 11.0592 MHz crystal oscillator
- Reset push button
- Interrupt push buttons
- LED indicators
- GPIO header pins (Ports P0–P3)
- This section forms the core programmable logic of the board.
  
# Repository Includes
- PCB Model
- Schematic
- Board images


