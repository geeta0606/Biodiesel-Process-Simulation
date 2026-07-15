# Biodiesel Process Simulation (Version 1)
## Overview
This project presents a steady-state simulation of a basic biodiesel production process developed using DWSIM. The process models the transesterification of triolein with methanol to produce methyl oleate (biodiesel) and glycerol.

The objective of this project was to gain hands-on experience with chemical process simulation, process flowsheet development, and material balance analysis.

## Features
- Steady-state process simulation
- Feed preparation and mixing
- Feed preheating
- Conversion reactor for transesterification
- Ideal product separation
- Material balance verification
- Stream composition analysis

## Software Used
- DWSIM 9.0.2

## Process Flowsheet

![Flowsheet](Flowsheet.png)


## Process Description
The simulated process consists of the following unit operations:
-Feed preparation
-Mixer
-Heater
-Conversion Reactor
-Compound Separator
The conversion reactor models the transesterification of triolein with methanol to produce biodiesel and glycerol. An ideal compound separator is used to isolate the biodiesel product stream.

## Reaction
Triolein+3Methanol→3Methyl Oleate+Glycerol
Reaction conversion:
- 95% Triolein Conversion

## Simulation Parameters

| Parameter | Value |
|-----------|-------|
| Software | DWSIM 9.0.2 |
| Property Package | NRTL |
| Simulation Type | Steady-State |
| Reactor Type | Conversion Reactor |
| Reactor Temperature | 333.15 K |
| Operating Pressure | 1 atm |
| Triolein Conversion | 95% |

## Repository Structure

```text
Biodiesel-Process-Simulation/
│
├── README.md
├── biodiesel_process_simulation_v1.dwxmz
├── Report.pdf
└── Images/
    ├── Flowsheet.png
    ├── Reactor.png
    ├── Product_Stream.png
    └── Results.png
```

## Key Learning Outcomes
- Process flowsheet development using DWSIM
- Configuration of a conversion reactor
- Process simulation under steady-state conditions
- Material balance verification
- Interpretation of stream compositions
- Basic downstream product separation

## Future Improvements
- Methanol recovery and recycle
- Flash separation
- Distillation-based purification
- Process optimization
- Equipment sizing
- Economic analysis
