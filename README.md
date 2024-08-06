# COREBOOT FOR T60 W/ INTEL GPU

All the content of this repository is provided without any kind of warranty, what you will do with the files I provide are your sole responsibility: in case of damage or any other problem I am not responsible. This project is for educational purposes only and I do not own the content of this repository!

--

DESCRIPTION

My coreboot build based on 662353ac3e75409512c0f49b978cda4c0b9fd7fe built on October 2, 2023 for IBM Thinkpad T60 with Intel Integrated GPU.

Not all components are free software: it contains the binary blob "vgabios.bin" extracted from the original IBM BIOS (using "bios_extract") and containing the proprietary firmware of the graphics card, it contains the latest updates to the microcode.

- Intel GPU Proprietary Firmware
- Intel CPU Microcodes Updates
- SEABIOS as payload

Tested on IBM Thinkpad T60 TYPE 1951 and flashed using the internal method with flashrom (without using a clip).

--

LICENSE

All coreboot code is released under the GNU GPL license (its license can be seen in the "COPYING" file), with the exception of the vgabios.bin file owned by Intel which is included for "fair use" as this is a project for educational purposes only.
