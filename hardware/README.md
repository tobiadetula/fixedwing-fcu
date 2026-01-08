# Hardware

This directory contains all hardware design files for the Fixed Wing Flight Control Unit (FCU).

## Directory Structure

### `/pcb`
PCB design files including:
- KiCad PCB layout files (.kicad_pcb)
- PCB project files
- Design rule check (DRC) reports
- Board stackup specifications

### `/schematics`
Schematic design files including:
- KiCad schematic files (.kicad_sch)
- Circuit diagrams
- Block diagrams
- Electrical characteristics

### `/cad`
Mechanical CAD files including:
- 3D models of the PCB
- Enclosure designs
- Mounting bracket designs
- STEP files for mechanical integration

### `/bom`
Bill of Materials including:
- Component lists
- Part numbers and specifications
- Supplier information
- Cost estimates

### `/gerbers`
Manufacturing files including:
- Gerber files for PCB fabrication
- Drill files
- Pick-and-place files
- Assembly drawings

### `/firmware`
Embedded firmware and bootloader files including:
- Source code references
- Binary files
- Flashing instructions
- Version information

## Design Tools

- **PCB Design**: KiCad 6.0 or later
- **CAD**: FreeCAD, Fusion 360, or SolidWorks
- **Version Control**: Git

## Getting Started

1. Install KiCad from https://www.kicad.org/
2. Open the project file in `/pcb` or `/schematics`
3. Review the design documentation in `/docs/design`
4. Check the BOM for required components

## Contributing

When making hardware changes:
1. Follow KiCad design rules
2. Update schematics and PCB layout together
3. Regenerate BOM and Gerbers after changes
4. Document all design decisions
5. Run DRC before committing
