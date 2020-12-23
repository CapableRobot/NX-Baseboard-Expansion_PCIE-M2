# NX Baseboard Expansion : PCIe m2 E-Key

This repository holds the open-source files for the PCIe m2 E-Key add-on to the NX Baseboard.  The [NX Baseboard](https://github.com/antmicro/jetson-nano-baseboard) is also open-source, is designed by Antmicro, and is [sold by Capable Robot Components](https://capablerobot.com/products/nx-baseboard/).

![PCIe m2 E-Key PCBA](https://capablerobot.imgix.net/images/products/CR69Z2.jpg?fit=fillmax&fill=solid&fill-color=FFFFFF&trim=color&trim-color=FFFFFF&pad=20&h=550&w=800&s=7458a1bf65c18ccde103b48de0a08ceb)

Assembled and tested PCBAs are available for purchase on the [Capable Robot website](https://capablerobot.com/products/nx-baseboard/).

The NX PCIe m.2 E Key PCB provides a standard interface to the NVIDIA NX's PCIe x1 bus, which is exposed on the NX Baseboard via a 10-pin FFC connector. Board specifications:

- m.2 E-Key (PCIe + USB), 2230 size. This is commonly used for WIFI modules like the Intel 8265.
- PCIe x1 interface and 3.3v power are connected to the Host via a 10-pin 0.5mm flex cable.
- USB interface exposed via micro-USB port, allowing USB-specific functionality of the installed card (like Bluetooth) to be used if cabled to the Host. With USB connected, a local 5v to 3.3v regulator can be used in lieu of the 3.3v input on the FFC connector.

Hole spacing on the PCB and location of the flex connector matches that of the NX Baseboard, allowing it to be assembled onto the bottom of the Baseboard.

Any WIFI module that supports m.2 E Key 2230 size can be used with the PCB. We recommend (and stock) the Intel 8265 due to built-in support within NVIDIA Jetpack BSPs.

## License Information

| **Type** | **License** |
| --- | --- |
| Hardware | Copyright Capable Robot Components 2020 <br><br>This source describes Open Hardware and is licensed under the [CERN-OHL-P v2](https://ohwr.org/cern_ohl_p_v2.txt). <br/><br/> You may redistribute and modify this documentation and make products using it under the terms of the [CERN-OHL-P v2](https:/cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-P v2 for applicable conditions |
| Software | NA |
| Documentation | [Creative Commons Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/) License |

More detailed information about the CERN License is available in the [license](license) folder and on the [CERN website](https://ohwr.org/project/cernohl/wikis/home).