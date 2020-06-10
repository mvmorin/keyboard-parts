# Keyboard Parts
KiCad library of MX and Alps compatible footprints and other miscellaneous footprints and symbols.

# Design
The main focus is the ease of PCB creation and design. Meaning, the switch footprints and symbol already have the diodes included. This eliminates almost half of the components and traces. Each switch footprint also comes with the corresponding plate-cutout for both MX and Alps switches, located on the *eco1* and *eco2* layer respectively. The PCB can then serve as the master for the plate with all the cutouts being exported as a single *dxf* (or other) file for the use in the plate design. They cutouts are mainly aimed at pcb/FR4 plates and are/will be dimensioned to accommodate the looser tolerances of PCB-milling.

# Known Issues
* Alps cutouts are a little tight. About 60% of the cutouts in the test print where too small.
* Cherry stabilizer cutout too small. All cutouts in the test print needed filing to fit at all.

# Untested Footprints
Footprint features that not have been test printed/manufactured:
* None

# Licenses
[![License: CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
The library is released under the [Creative Commons CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) license, Copyright (c) Martin Morin 2020.
Some footprints and symbols are based on parts from the [KiCad libraries](https://kicad-pcb.org/libraries/), released under the same [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) license.
