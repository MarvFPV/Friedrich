# Friedrich
50% 3D printed keyboard designed to be printable on regular sized 3d printers.

This place is designed to be 3d printed with a regular FDM printer, beware of that when ordering it from any other material. 

To make the case printable on regular machines, i had to cut it in half. To fuse those halves together you can either use super glue or melt them together by running a (clean) soldering iron tip through the seam (my preferred way). Make sure to re-tin your soldering iron afterwards tho as this process may damage your tip.

## Required components for handwires
* 52 MX style switches
* 2 2u MX platemount stabs
* 1 6.25u MX platemount stab
* 52 Diodes
* a Promicro
* one of ai03's [unified daughterboards](https://github.com/ai03-2725/Unified-Daughterboard)
* a few cables to wire up the matrix
* 4 m3x6mm screws
* 6 m3x8mm countersunk screws

I personally tend to remove the microUSB connector from the Promicro and solder it directly to a unified daughterboard, that's also why the Promicro cutout may not fit with the USB connector still on the PCB. (I should really write up some documentation on that ^^)

## PCB version
The PCB is not yet compatible with the switch plate in the repo, some cutting / melting away will have to be done to get it to fit with PCBmount stabs. Or just annoy me to add it ^^
