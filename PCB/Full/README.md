# SHKB
A alternative controller for the HHKB pro 2 with integrated hub. The full-version features a SuperSpeed 5.0 Gbps USB 3.1 Hub, the lite-version features a USB 2.0 MTT hub. The lite-version is available in both USB-mini and USB-C. SHKB lite mini is a drop in replacement for the original PCB, the c-version will need modification of the Pro 2 case in the same way as the full-version.

## Status - full:
- Prototype round 2 of Rev A. PCB produced and delivered to testers, currently 5 PCB's being used, two HHKB JP, three regular ANSI. So far working great.
- 2021-03-16: New proto-run being made with some changed components better suited for manufacturing and connectors that better fits custom projects.
- 2021-06-29: New proto-run being made with fixed issues on the USB-A connectors introduced in revision B1. Minor trace-tweaks and a new inductor for the 1.1v regulator.

## **Note - full:**
- Rev A is tested and works properly.
- **Rev B is a work in progress. Base functionality is tested. Need to do long term testing and verify USB 3.0 speeds and reliability.**

## Features:
- 3 available USB3 ports, two external, one internal. Hub: TUSB8042A
- ATMEGA32U4 for keyboard firmware (TMK/QMK/VIA), uses current implementations for HHKB
- 900mA per port current limit on each downstream port using TPS2552D
- Will require modification of hhkb case because of the usb-c connector

## PCB
![alt text](./readme-images/rev_b3.jpg "Altium 3D")

Thread on GH: https://geekhack.org/index.php?topic=93970.0

## Future work
- Test and verify revision B3.
- Add build guide and flash instructions

<a href='https://ko-fi.com/4pplet' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />

## Status - Lite:
- 2022-03-16: Initial prototype round ordered for mini-version. Files for protos is added as pre-release. Untested.
