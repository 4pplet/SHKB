# SHKB
A alternative controller for the HHKB with integrated SuperSpeed 5.0 Gbps USB 3.1 Hub.

## Status:
Prototype round 2. PCB produced and delivered to testers, currently 5 PCB's being used, two HHKB JP, three regular ANSI.

## Some features:
- 3 available USB3 ports, two external, one internal. Hub: TUSB8042
- ATMEGA32U4 for keyboard firmware (TMK/QMK)
- 900mA per port current limit on each downstream port using TPS2552D
- Will need modification of hhkb case because of the usb-c connector

## Altium view of PCB
![alt text](./readme-images/altium-3d.jpg "Altium 3D")

Thread on GH: https://geekhack.org/index.php?topic=93970.0

## Future work
- Evaluate different USB-A connectors.
- Investigate cheaper hubs, possibly with integrated usb-c mux and regulators.
- Investigate switching to ganged current limit to cut cost.
