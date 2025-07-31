# CivicAlert Hardware Design Repository

This repository contains hardware design files for the CivicAlert sensor device. The design was created
using [KiCad](https://www.kicad.org/download) and requires v9.0.0 or later to open and edit.


## Getting Started

1. Clone this repo on your local machine
2. Download and install [KiCad](https://www.kicad.org/download)
3. Open KiCad
4. Click `File->Open Project->hw.kicad_pro` located in the root of the directory where you stored the repo

You will be presented with a listing of available KiCad tools for this project. The two most relevant are
the "Schematic Editor" and the "PCB Editor". The Schematic Editor allows you to view and manipulate the
logical connections between hardware components and power networks, while the "PCB Editor" allows you to
view the actual design of the board and layout of the components as they will be placed during
manufacturing and assembly.

The schematic symbols and footprints for all parts and components used in this design have been stored
within the repo itself and should automatically be picked up by KiCad when you open the project. If you
would like to add new parts or alter existing ones, you may use the "Symbol Editor" or "Footprint
Editor" tool, and ensure that any new parts are stored in either `/part_symbols` or `/part_footprints`
so that new parts will be visible and available to others who clone this repository in the future.


## Revisions

### Revision A

This is the original prototype version of the hardware. The major functionality and components are shown
in the following graphics:

TODO

### Revision B

TODO
