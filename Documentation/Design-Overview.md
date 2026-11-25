# Hardware Design Overview

The PIC18F2550 development board provides access to microcontroller signals for embedded development and prototyping. The designer-approved fabrication dimensions are 68 × 46 mm. The earlier PCB preview shows 67 × 45 mm and is retained as a historical design illustration.

## Functional blocks

- PIC18F2550-I/SP microcontroller in a DIP-28 package.
- L7805CV regulator and DC jack input.
- PORT A, PORT B and PORT C breakout headers.
- ICSP header and manual reset circuit.
- External oscillator header with two 22 pF capacitors.
- Power indicator LED and ground access header.

## Component reference

| Reference | Value or description shown in the schematic |
| --- | --- |
| U1 | PIC18F2550-I/SP |
| U2 | L7805CV |
| J1 | DC jack |
| D1 | LED |
| R1 | 330 Ω |
| R2 | 10 kΩ |
| C1, C3 | 22 pF |
| C2, C11 | 100 nF |
| C4 | 1 µF |
| C5 | 100 µF |
| SW1 | Tactile reset switch |
| P1–P7 | Connectors / headers |

This is a schematic-derived reference, not a procurement BOM.

## Verification and fabrication

The designer reports that the hardware has been tested and is ready for fabrication. Gerber and NC drill production outputs are available in [Manufacturing](../Manufacturing/README.md). Detailed test records and ERC/DRC reports are not included. The native schematic and PCB are preserved without electrical or layout changes.
