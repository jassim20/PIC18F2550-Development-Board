# Fabrication Outputs

Native Gerber and NC drill exports supplied by the designer, generated on 2026-11-16. Gerber metadata identifies Altium Designer 26.1.1 (7).

## Contents

- `Gerber/`: original Gerber layers and aperture/export reports (including empty paste and bottom overlay layers).
- `NC-Drill/`: original plated through-hole drill data and drill report.
- `PIC18F2550-Fabrication.zip`: flat archive containing the two copper layers, two solder mask layers, top silkscreen, profile (`PIC18F.GM`) and plated drill file. Empty layers and auxiliary reports are not required in this fabrication archive.

## Inspection

- Gerber: millimetres, absolute 4:4 coordinate format.
- NC drill: millimetres, 4:4 coordinate format, 97 plated round holes across six tools.
- All 97 hole centres match flashed pad centres in both copper and both solder mask layers.
- Drill tool sizes: 0.800 mm (12), 0.830 mm (28), 1.000 mm (43), 1.016 mm (8), 1.270 mm (3), 3.000 mm (3).
- The profile centreline spans 68 x 46 mm, whereas the earlier PCB preview and project documentation state 67 x 45 mm. Confirm the intended physical board outline in Altium before releasing these manufacturing outputs or ordering boards.

This is a coordinate and file-content inspection, not a full DFM, ERC or DRC certification. The designer reports the hardware has been tested. No source design or fabrication layer data has been modified.

The auxiliary `.LDP` file was omitted from public distribution because it contains a local workstation path. The drill report and actual drill data are retained.
