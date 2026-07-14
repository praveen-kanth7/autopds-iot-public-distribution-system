Hardware

This directory contains all the hardware design resources for the **AutoPDS: An IoT-Enabled Automated Public Distribution System**.

Contents

Block Diagram
Illustrates the overall system architecture and the interaction between hardware components.

Circuit Diagram
Shows the complete electrical connections between the ESP32, RFID reader, load cell, HX711 amplifier, servo motor, LCD display, power supply, and other peripherals.

Wiring Diagram
Provides detailed pin-to-pin connections for assembling the hardware prototype.



Hardware Components

| Component | Purpose |
|----------|---------|
| ESP32 | Main microcontroller |
| RC522 RFID Reader | Beneficiary authentication |
| HX711 | Load cell amplifier |
| Load Cell | Weight measurement |
| Servo Motor | Controls ration dispensing |
| LCD Display | User interface |
| Power Supply | Powers the system |

Folder Structure

```text
hardware/
├── block-diagram/
├── circuit-diagram/
├── wiring/
└── pcb/
```

Notes

The diagrams and design files in this directory are intended to help understand, assemble, and maintain the AutoPDS hardware prototype.
