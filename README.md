# PIC18F2550 Development Board

A compact microcontroller development board designed in Altium Designer for embedded systems prototyping and PIC peripheral experiments.

**Design status:** Schematic and PCB layout prepared; electrical verification and hardware testing not yet confirmed.

## Project Overview

The board is based on the Microchip PIC18F2550-I/SP microcontroller in a 28-pin DIP package. It brings out GPIO signals and provides a regulated power supply, a programming header, a reset circuit, and an external oscillator connection.

## Hardware Features

| Feature | Design specification |
| --- | --- |
| Microcontroller | PIC18F2550-I/SP (DIP-28) |
| Power regulation | L7805CV, nominal 5 V output |
| Power input | DC barrel jack |
| GPIO expansion | PORT A, PORT B and PORT C headers |
| Programming | Intended ICSP interface |
| Clock | External oscillator header with 22 pF capacitors |
| Reset | Push button with 10 kΩ pull-up |
| Indicator | Power LED |
| PCB dimensions | 67 × 45 mm (nominal) |
| Design software | Altium Designer |

## Design Previews

Schematic, 2D PCB layout and 3D render will be added with the design assets.

## Planned Repository Structure

```text
PIC18F2550-Development-Board/
├── Hardware/
│   ├── Schematic/
│   └── PCB/
├── Images/
├── Documentation/
├── README.md
└── CHANGELOG.md
```

## Verification Roadmap

- [x] Schematic captured
- [x] PCB layout prepared
- [x] 3D design preview prepared
- [ ] Review ICSP signal mapping and GPIO net labels against the device pinout
- [ ] Verify power connections and component footprints
- [ ] Complete electrical and design rule checks (ERC/DRC)
- [ ] Publish source files and design previews
- [ ] Validate manufacturing outputs
- [ ] Assemble and test hardware

## Release Status

Initial design documentation. No validated hardware or production-ready release is claimed.

## License

No license has been selected yet.
