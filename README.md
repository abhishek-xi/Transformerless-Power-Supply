# Transformerless Power Supply PCB Project

This repository contains the KiCad project files for a **Transformerless Power Supply**.

## Description
KiCad-based PCB design for a transformerless power supply circuit. The design provides AC to DC conversion using passive and active components without a bulky transformer, making it compact and cost-effective for low-power embedded or household electronics applications. Includes schematic, PCB layout, and Gerber files for fabrication.

## Contents
- `*.kicad_sch` – Main schematic
- `*.kicad_pcb` – PCB layout
- `*.kicad_pro` – Project configuration
- `*.drl` – Drill file
- `Gerber files` – Gerber outputs for fabrication

## How to Open
1. Install [KiCad](https://www.kicad.org/) (version 6 or newer recommended).
2. Clone this repository.
3. Open the project using the `.kicad_pro` file.

## Safety Note ⚠️
Transformerless power supplies operate directly from AC mains. They **do not provide galvanic isolation** and can be extremely dangerous if mishandled. These designs are recommended only for experienced users and low-power applications. Use caution and follow all electrical safety practices.

## License
[MIT License](LICENSE) – You are free to use, modify, and distribute this project.
