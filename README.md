# PIC18F2550 Development Board

A compact microcontroller development board designed in Altium Designer for embedded systems prototyping and PIC peripheral experiments.

**Design status:** Hardware tested and approved for fabrication by the designer.

![3D render of the PIC18F2550 development board](Images/03-pcb-3d.png)

## Project Overview

The board is based on the Microchip PIC18F2550-I/SP microcontroller in a 28-pin DIP package. It provides GPIO breakout headers, regulated power, a programming interface, manual reset, and an external oscillator connection.

## Hardware Features

| Feature | Design specification |
| --- | --- |
| Microcontroller | PIC18F2550-I/SP (DIP-28) |
| Power regulation | L7805CV, nominal 5 V output |
| Power input | DC barrel jack |
| GPIO expansion | PORT A, PORT B and PORT C headers |
| Programming | ICSP header |
| Clock | External oscillator header with 22 pF capacitors |
| Reset | Push button with 10 kΩ pull-up |
| Indicator | Power LED |
| PCB dimensions | 67 × 45 mm (nominal) |
| Design software | Altium Designer |

## Design Previews

### Schematic

![Schematic](Images/01-schematic.png)

### PCB Layout

![2D PCB layout](Images/02-pcb-2d.png)

## Design Source Files

| File | Description |
| --- | --- |
| [PIC.SchDoc](Hardware/Schematic/PIC.SchDoc) | Native Altium schematic |
| [PIC18F.PcbDoc](Hardware/PCB/PIC18F.PcbDoc) | Native Altium PCB layout |
| [Design overview](Documentation/Design-Overview.md) | Functional blocks and component reference |
| [Changelog](CHANGELOG.md) | Revision history |

The native design files are provided as supplied. Open them in Altium Designer. A separate Altium project file and component libraries are not included.

## Repository Structure

```text
PIC18F2550-Development-Board/
├── Hardware/
│   ├── Schematic/PIC.SchDoc
│   └── PCB/PIC18F.PcbDoc
├── Images/
│   ├── 01-schematic.png
│   ├── 02-pcb-2d.png
│   └── 03-pcb-3d.png
├── Documentation/Design-Overview.md
├── README.md
├── CHANGELOG.md
└── .gitignore
```

## Verification and Manufacturing

- Hardware testing and fabrication readiness are reported by the designer.
- Schematic, PCB layout and design previews are included.
- Detailed test records, ERC/DRC reports, procurement BOM, Gerber and NC drill files are not included. Generate and check manufacturing outputs in Altium Designer before ordering boards.

## Release Status

Initial hardware release: [v1.0.0](https://github.com/jassim20/PIC18F2550-Development-Board/releases/tag/v1.0.0), published on 2026-11-25. The release includes the native design files, design previews and technical documentation.

## License

No license has been selected yet.
