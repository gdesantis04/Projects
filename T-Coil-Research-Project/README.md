# PCB-Embedded T-Coil for Expanding Channel Bandwidth

This repository contains the design files and documentation for a PCB-embedded bridged T-coil project. The goal of the project was to compensate for heavy load capacitance, such as capacitance introduced by ESD protection, and improve high-frequency channel bandwidth using PCB-embedded inductors. 

## Project Summary

The project investigates a bridged T-coil implemented with PCB transmission-line structures. The design was supported by simulation and layout work, then validated through fabricated-board measurements. The final result showed that the fabricated T-coils reduced loss on channels with parasitic capacitance. We tried to implement the same technique that Nvidia is using on SERDES chips on transmission lines in the Gigahertz range. Our advisor for this project was Dr. Thanh Tran at Rice University. 

## Repository Structure

```text
T-Coil-Research-Project/
├── README.md
├── .gitignore
├── docs/
│   ├── T-Coil-Paper.pdf
│   └── T-Coil-Design-Presentation.pdf
├── kicad/
│   ├── t-coil3.kicad_pro
│   ├── t-coil3.kicad_sch
│   ├── t-coil3.kicad_pcb
│   ├── t-coil3.kicad_prl
│   └── t-coil3.hyp
└── fabrication/
    ├── t-coil3-odb.zip
    └── gerbers/
```

## Contents

- `docs/` contains the final paper and project presentation.
- `kicad/` contains the KiCad schematic, PCB layout, project file, and HyperLynx file.
- `fabrication/` contains manufacturing outputs, including Gerbers, drill files, and an ODB++ archive.

## Tools Used

- KiCad for schematic capture and PCB layout
- Ansys HFSS and Siemens HyperLynx for simulation and electromagnetic design support
- Vector network analyzer measurements for experimental validation

## Authors

Mitchell Hoffman, Zheng Wei Low, and Guido De Santis  
Department of Electrical and Computer Engineering, Rice University

## Notes

This repository has been cleaned for GitHub. Temporary files, macOS metadata, KiCad lock files, local cache files, and automatic backup archives were removed.
