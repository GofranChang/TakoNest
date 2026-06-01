# TakoNest

A case design for [Tako](https://github.com/ssbb/tako), a 34-key electrostatic capacitive split keyboard.

TakoNest is an experimental/custom case project for Tako.  
The goal is to provide a more complete case-style enclosure for Tako while keeping the original PCB and plate compatibility as much as possible.

> ⚠️ This project is still a work in progress.  
> Please verify all dimensions before printing or building.

---

## Preview

<!-- Add renders or photos here -->

<!--
![TakoNest Render](images/render.png)
![TakoNest Build](images/build.jpg)
-->

---

## Files

```text
TakoNest/
├── step/
│   ├── main.step      # Main case model
│   └── plate.dxf      # Plate / outline DXF
└── README.md
```

### `step/main.step`

Main 3D model of the case.  
This file can be used for:

- 3D printing preparation
- CAD modification
- Fit checking with the Tako PCB / plate

### `step/plate.dxf`

2D plate / outline file.  
This file can be used for:

- Dimension checking
- Importing into CAD software

---

## Compatibility

This case is designed for the original [ssbb/tako](https://github.com/ssbb/tako) EC split keyboard.

Tako is a vertical-stagger split keyboard using electrostatic capacitive non-contact switches.  
Please refer to the original Tako repository for PCB, firmware, EC parts, and build information.

### Important Notes

Before ordering or manufacturing parts, please check:

- PCB outline compatibility
- Plate thickness
- Screw hole positions
- Standoff height
- USB / power switch / reset switch clearance
- Battery clearance for wireless builds
- EC housing and slider clearance
- Left / right hand mirroring

The original Tako project has different plate requirements depending on the EC parts used:

- OG-style plate: usually 1.2 mm
- NIZ-style plate: usually 1.6 mm

Please confirm the plate type before production.

---

## Manufacturing

### 3D Printing

Recommended for quick prototyping and fit testing.

Suggested materials:

- PLA / PLA+
- PETG
- ABS / ASA
- Resin, if high detail is needed

For FDM printing, recommended settings:

- Layer height: 0.12 mm - 0.20 mm
- Wall loops: 3+
- Infill: 20%+
- Support: depends on orientation
- Print one side first before printing a full pair

Recommended checks after printing:

- PCB can sit flat
- Screw holes align correctly
- Keycaps do not rub the case
- USB port is accessible
- Power switch is accessible
- Bottom clearance is enough for components / battery

---

## Assembly Notes

A typical build may require:

- Tako PCB
- Tako-compatible EC plate
- EC housings
- EC domes
- EC conical springs
- MX-compatible EC sliders
- Keycaps
- MCU / controller
- Screws and standoffs
- Battery, for wireless builds

This repository only provides case-related files.  
For electronics, firmware, and EC switch parts, please refer to the original Tako project.

---

## Design Goal

TakoNest is intended to make Tako feel more like a complete custom keyboard rather than a bare PCB / plate build.

The design direction is:

- Rounded
- Compact
- Case-integrated
- Suitable for EC typing feel
- Friendly to 3D printing and future revisions

---

## Status

Current status:

- [x] Initial STEP model
- [x] DXF plate / outline file
- [x] Test print
- [x] Fit check with PCB
- [ ] Screw / standoff verification
- [ ] Build photos
- [ ] Assembly guide

---

## Disclaimer

This is an unofficial case project for Tako.

The files are provided as-is.  
Please verify dimensions and tolerances before printing or assembling the case.

Use at your own risk.

---

## Credits

- Original keyboard project: [ssbb/tako](https://github.com/ssbb/tako)
- Case design: [GofranChang](https://github.com/GofranChang)

Special thanks to the open-source keyboard community and the EC keyboard community.

---

## License

This project is released under the MIT License.

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the files, as long as the original copyright notice and license text are included.

See the `LICENSE` file for details.
