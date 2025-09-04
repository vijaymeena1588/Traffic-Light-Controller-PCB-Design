# PCB_Implement
Developed a proof-of-concept traffic signal controller using Atmega328P microcontroller, RGB LEDs, and a seven-segment countdown timer. Designed schematic diagrams and created a PCB layout using Autodesk Eagle, followed by Gerber file generation for fabrication. Successfully implemented the circuit to simulate real-world traffic signal operation. My role included microcontroller programming, PCB design, and hardware testing. The project outcome demonstrated efficient traffic control automation with a reliable and cost-effective PCB-based solution.

## Eagle Libraries Used in This PCB Design

The following Eagle libraries (`.lbr` files) are used in this project:

- **PC_CON_DC_Power_Jack.lbr** – DC power jack connector
- **PC_CON_ScrewTerminal_2P_5mm.lbr** – Screw terminal (2-pin, 5mm pitch)
- **PC_Capacitor_0603.lbr** – Capacitors (0603 package)
- **PC_IC_ATMEGA328-AU.lbr** – ATmega328 (TQFP package)
- **PC_IC_ATMEGA328P-AU.lbr** – ATmega328P (TQFP package)
- **PC_IC_CD4511BE.lbr** – CD4511BE IC
- **PC_IC_L7805ABD2T-TR.lbr** – 7805 voltage regulator (D2PAK package)
- **PC_IC_L7805_TO252.lbr** – 7805 voltage regulator (TO-252 package)
- **PC_LED-7-SegmentDisplay.lbr** – 7-segment LED display
- **PC_Resistor_0603.lbr** – Resistors (0603 package)
- **PC_Switch_1437566-3.lbr** – Pushbutton switch

These libraries were added to support the schematic symbols, footprints, and 3D packages required in the PCB design.

## Hardware Block Diagram

The following block diagram represents the overall design of the hardware:

![Hardware Block Diagram](Hardware%20Block%20Diagram.png)

---

## Hardware Layout with Sections

This image highlights the different sections of the hardware on the PCB:

![Hardware Image with sections](Hardware%20Image%20with%20sections.png)
