# TakoNest

A custom case project for [Tako](https://github.com/ssbb/tako), a 34-key electrostatic capacitive split keyboard.

TakoNest is an unofficial case design that aims to make Tako feel more like a complete custom keyboard, while keeping compatibility with the original PCB and EC plate structure.

> ⚠️ This project is still a work in progress.
> Please verify all dimensions before printing or manufacturing parts.

## Features

- Rounded case design for the Tako EC split keyboard
- FDM-friendly geometry
- Integrated top cover style
- Supports the original Tako PCB layout
- Designed around EC typing feel and clearance requirements
- Magnetic palm rest design in progress

## Preview

Images and build photos will be added as the design is refined.

## Repository Structure

```text
TakoNest/
├── models/        # STEP / STL / CAD files
├── plates/        # Plate DXF / cutting files
├── images/        # Photos and renders
└── README.md
```

## Compatibility

This case is designed for the original [ssbb/tako](https://github.com/ssbb/tako) electrostatic capacitive split keyboard.

Please refer to the original Tako repository for:

* PCB files
* Firmware
* EC switch parts
* Build information
* Original plate requirements

Before printing or manufacturing parts, please check:

* PCB outline compatibility
* Plate thickness
* Screw hole positions
* Standoff height
* USB / power switch / reset switch clearance
* Battery clearance for wireless builds
* EC housing and slider clearance
* Left / right hand mirroring

The original Tako project may require different plate thicknesses depending on the EC parts used:

* OG-style / DES-style plate: usually 1.2 mm
* NIZ-style plate: usually 1.6 mm

Please confirm the plate type before production.

## Manufacturing Notes

### 3D Printing

FDM printing is recommended for prototyping and personal builds.

Suggested materials:

* PLA / PLA Matte
* PLA+
* PETG
* ABS / ASA

Recommended FDM settings:

* Layer height: 0.12 mm - 0.20 mm
* Wall loops: 3+
* Infill: 20%+
* Print one side first before printing a full pair
* Check all clearances before final assembly

Recommended checks after printing:

* PCB can sit flat
* Screw holes align correctly
* Keycaps do not rub the case
* USB port is accessible
* Power switch / reset switch is accessible
* Bottom clearance is enough for components and battery

## Assembly Notes

A typical build may require:

* Tako PCB
* Tako-compatible EC plate
* EC housings
* EC domes
* EC conical springs
* EC sliders
* Keycaps
* MCU / controller
* Screws and standoffs
* Battery, for wireless builds

This repository only provides case-related files.
For electronics, firmware, and EC switch parts, please refer to the original Tako project.

## Design Goal

TakoNest is intended to make Tako feel more like a complete custom keyboard rather than a bare PCB / plate build.

The design direction is:

* Rounded
* Compact
* Case-integrated
* Inspired by vintage plastic electronics
* Suitable for EC typing feel
* Friendly to FDM printing and future revisions

## Status

Current status:

- Prototype case printed
- Fit check with PCB in progress
- Screw / standoff verification in progress
- Magnetic palm rest is still being designed
- Files will be updated as issues are fixed

## Magnetic Palm Rest

A matching magnetic palm rest is planned for TakoNest.

The current goal is to design a separate palm rest that attaches to the front side of the case with magnets, while keeping the case easy to print and assemble.

This part is still in progress and may change in future revisions.


## Disclaimer

This is an unofficial third-party case project for Tako.

The files are provided as-is.
Please verify dimensions and tolerances before printing or assembling the case.

Use at your own risk.

## Credits

* Original keyboard project: [ssbb/tako](https://github.com/ssbb/tako)
* Case design: [GofranChang](https://github.com/GofranChang)

Special thanks to the open-source keyboard community and the EC keyboard community.

## License

TakoNest case files are released under **CC BY-NC-SA 4.0**.

You may:

* Use the files for personal builds
* Modify the files for personal use
* Share remixes under the same license
* Study and learn from the design

You may not:

* Sell printed parts
* Sell kits based on this design
* Use the files or derivatives for commercial purposes without permission

For commercial use, please contact the author.

The original Tako keyboard project remains under its own license.
