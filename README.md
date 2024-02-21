# RISC-V VSDQUADRON


- [All about RISC-V VSDQUADRON](#all-about-risc-v-vsdquadron)
- [Board Overview](#board-overview)
- [Project Introduction](#project-introduction)
- [Reference Diagram](#reference-diagram)

# All about RISC-V VSDQUADRON

The VSDSquadron Mini RISC-V development board- Features and Interfaces:
 
 
 - Core Processor- The board is powered by CH32V003F4U6 chip with 32-bit RISC-V core based
 on RV32ECinstruction set, optimized for high-performance computing with support for 2-level
 interrupt nesting and supports 24MHz system main frequency in the product function
 
 - Clock and Reset Systems: Includes a built-in factory-trimmed 24MHz RC oscillator and a
 128kHz RCoscillator, plus an external 24MHz oscillator option for varied clocking requirements.
 
 - Robust GPIO Support: Boasts 3 groups of GPIO ports, totaling 15 I/O ports, enabling
 extensive peripheral connections and mapping to external interrupt capabilities.
 
 - Flexible Communication Interfaces: Offers multiple communication protocols including US
ART, I2C, and SPI for versatile connectivity options.

 - High-Speed Memory: Equipped with 2KB SRAM for volatile data storage, 16KB CodeFlash
 for program memory, and additional 1920B for bootloader functionalities.
 
 - On-board Programmer: Features on-board CH32V305FBP6 single-wire programming protocol, enhancing development efficiency with seamless code deployment and debugging. NO NEED to purchase any additional adapter.

   ![Screenshot 2024-02-21 225655](https://github.com/mzmdirfan/RSIC-V-vsdsquadron/assets/100523407/a634c0dc-9602-4b24-a75f-78ba2490cbde)

 # Board Overview
 The VSDSquadron Mini RISC-V development boards features a RISC-V SoC with the following
 capabilities:
 
 - On-board 24MHz RC oscillator.
 - 3 groups of GPIO ports, totaling 15 I/O ports.
 - USART, I2C, and SPI.
 - UART implemented on USART.
 - 2KB SRAM for volatile data storage, 16KB CodeFlash for program memory.
 - On-board Programmer. NO NEED of any additional adapter.

 # Project Introduction

  - Web Server:  Control an LED from Webpage

 # Reference Diagram

   ![Circuit-Diagram-for-ESP32-Web-Server](https://github.com/mzmdirfan/RSIC-V-vsdsquadron/assets/100523407/ec941fa4-d937-431c-8e03-f7ccc9054f55)

   Source: https://iotdesignpro.com/projects/esp32-web-server-control-led-from-webpage
