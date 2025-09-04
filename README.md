# Traffic Light Controller – PCB Design Project

## Project Overview
This project demonstrates the design and development of a **proof-of-concept traffic signal controller** using a custom-designed PCB.  
The hardware integrates an **ATmega328P microcontroller**, **RGB LEDs** for traffic light indication, and **dual 7-segment displays with driver circuitry** for countdown functionality.  
The PCB was designed using **Autodesk Eagle**, with schematic creation, component footprint integration, PCB layout, and Gerber file generation carried out as part of the workflow.  

---

## Technical Description
The traffic light controller was designed to simulate real-world traffic management systems with countdown functionality. The project involved:  

- **Microcontroller Integration:** ATmega328P served as the core MCU for control logic and timing.  
- **Traffic Indication:** RGB LEDs were configured as red, yellow, and green traffic lights.  
- **Countdown Display:** Two 7-segment displays, driven by IC CD4511BE, were used to show a two-digit countdown timer.  
- **Power Supply Design:** Onboard regulation using L7805 (TO-252 and D2PAK variants) provided a stable 5V supply from a DC jack or screw terminal input.  
- **Passive Components:** 0603 package resistors and capacitors were used for compact and reliable circuit implementation.  
- **Switching Mechanism:** A tactile pushbutton switch was included for reset/control functionality.  

The entire workflow included schematic capture, PCB layout routing, ERC/DRC validation, and generation of Gerber files for fabrication.  

---

## Key Contributions
- Designed the complete **schematic diagram** and created custom PCB footprints for unavailable components.  
- Optimized PCB layout for minimal routing complexity and reliable signal integrity.  
- Generated **Gerber files, BOM, and assembly drawings** for PCB manufacturing.  
- Conducted **simulation and hardware testing** to validate real-world traffic light sequencing.  
- Implemented **microcontroller programming** to manage timing, LED sequencing, and countdown display.  

---

## Features
- Fully functional **POC traffic light controller**.  
- Modular design enabling easy scaling for more lanes or advanced logic.  
- Compact PCB layout with industry-standard 0603 SMD components.  
- Reliable **5V regulated power supply** designed for low-noise operation.  
- Cost-effective solution with minimal component count and optimized PCB area.  

---

## Eagle Libraries Used
Custom and third-party Eagle libraries were used to support the required components:

- **PC_CON_DC_Power_Jack.lbr** – DC power input connector  
- **PC_CON_ScrewTerminal_2P_5mm.lbr** – Screw terminal (2-pin, 5mm pitch)  
- **PC_Capacitor_0603.lbr** – SMD capacitors (0603 package)  
- **PC_IC_ATMEGA328-AU.lbr** – ATmega328 (TQFP package)  
- **PC_IC_ATMEGA328P-AU.lbr** – ATmega328P (TQFP package)  
- **PC_IC_CD4511BE.lbr** – 7-segment display driver IC  
- **PC_IC_L7805ABD2T-TR.lbr** – 7805 voltage regulator (D2PAK package)  
- **PC_IC_L7805_TO252.lbr** – 7805 voltage regulator (TO-252 package)  
- **PC_LED-7-SegmentDisplay.lbr** – 7-segment LED display  
- **PC_Resistor_0603.lbr** – SMD resistors (0603 package)  
- **PC_Switch_1437566-3.lbr** – Pushbutton switch  

---

## Hardware Block Diagram
![Hardware Block Diagram](Hardware%20Block%20Diagram.png)

---

## Hardware Layout with Sections
![Hardware Image with sections](Hardware%20Image%20with%20sections.png)

---

## Deliverables
- **Schematic file (.sch)**  
- **Board layout file (.brd)**  
- **Gerber files** for fabrication  
- **Bill of Materials (BOM)**  
- **Assembly drawing** for reference  

---

## Conclusion
This project successfully demonstrates the use of **PCB design techniques, embedded system integration, and hardware testing** to create a functional traffic signal controller.  
The outcome highlights the ability to merge **microcontroller programming with practical PCB implementation**, resulting in a **reliable, scalable, and cost-effective hardware prototype** for traffic management applications.  
