# Babel-Babel combined debugger and interface converter business requirements

## Purpose

Babel-Babel is a device intended to ease the process of manufacturing flashing and testing of Zubax products (or any other similar products).
Besides that, the device can be used as a tool for UAVCAN-compatible embedded devices.
One Babel-Bable can replace two USB-CAN converters, a programmer and also can provide one USB 2.0 port for connecting of the device being debugged.
All this requires only 1 USB connection to the host PC.

## Technical requirements


* small size.
* minimizing the required USB connections number for the host PCB to the debugging tools.
* minimizing the required cable connections number to the device under test.
* The hardware should be compatible with the existing software for Babel and DCP 2.3. 

## Design requirements

* USB connectors should be able to tolerate moderate mechanical abuse. 
* Enclosure class IP40
* Standard Dronecode connector should be used for SWD interface and debug UART.
* USB-CAN converters should be compatible with UAVCAN hardware recommendations.
* The device should be powered from the USB bus (4.5 - 5.5 V, current consumption up to 500 mA).

## Environmental conditions.

* In-door usage.
* Operating temperature range - 0..+40C
* Operating Humidty - up to 100% 

Using non-AEC-Q grade components as well as deviations from the hardware development policies is allowed.
