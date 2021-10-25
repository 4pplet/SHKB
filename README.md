# SHKB
A alternative controller for the HHKB with integrated SuperSpeed 5.0 Gbps USB 3.1 Hub.

## Status:
- Prototype round 2 of Rev A. PCB produced and delivered to testers, currently 5 PCB's being used, two HHKB JP, three regular ANSI. So far working great.
- 2021-03-16: New proto-run being made with some changed components better suited for manufacturing and connectors that better fits custom projects.
- 2021-06-29: New proto-run being made with fixed issues on the USB-A connectors introduced in revision B1. Minor trace-tweaks and a new inductor for the 1.1v regulator.

## **Note:**
- Rev A is tested and works properly.
- **Rev B is a work in progress. Currently waiting for protos.**

## Some features:
- 3 available USB3 ports, two external, one internal. Hub: TUSB8042A
- ATMEGA32U4 for keyboard firmware (TMK/QMK/VIA), uses current implementations for HHKB
- 900mA per port current limit on each downstream port using TPS2552D
- Will need modification of hhkb case because of the usb-c connector

## Altium view of PCB
![alt text](./readme-images/rev_b3.jpg "Altium 3D")

Thread on GH: https://geekhack.org/index.php?topic=93970.0

## Future work
- Test and verify revision B3.
