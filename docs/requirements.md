# Business requirements for Babel-Babel

## Purpose

Babel-Babel is a device intended to ease the process of flashing and testing of Zubax products (or similar products).
Besides that, the device can be used as a tool for developing and debugging UAVCAN-compatible embedded devices.
One Babel-Babel can replace two USB-CAN converters, a programmer, and provide one free USB 2.0 host port.
All this requires a single USB connection to the host PC.

## Technical requirements

* Small size.
* Minimizing the number of required USB connections to the host PCB.
* Minimizing the number of required cable connections to the device under test.
* The hardware should be compatible with the existing software for Babel and DCP 2.x.

## Design requirements

* USB connectors should be able to tolerate moderate mechanical abuse.
* Enclosure class IP40.
* Standard Dronecode connector should be used for SWD interface and debug UART.
* USB-CAN converters should be compatible with Dronecode DS-015 hardware design recommendations.
* The device should be powered from the USB bus (4.5 - 5.5 V, current consumption up to 500 mA).
* Usage of non-AEC-Q grade components, as well as deviations from the hardware development policies, are allowed.

## Environmental conditions

* In-door usage.
* Operating temperature range - 0..+40C
* Operating humidty - up to 100%
