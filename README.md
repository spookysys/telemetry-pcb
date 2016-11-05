# A brain for my rocket

## Features 

* Arduino-compatible
* Adafruit Feather M0 firmware and pinout
* Small size - fits the smallest model rockets (e.g. 26mm diameter)
* Powerful MCU (Atmel ARM M0 at 32MHz)
* GSM/GPRS for telemetry (SIM868)
* GPS for positioning (SIM868)
* 9-DOF Inertial Motion Unit (MPU-9259)
* Altimeter (BMP-280)
* MicroSD for logging
* Integrated usb-port, lipo-charger and power switch
* Integrated 5-volt/2-amp supply for powering motors and servos


## Adafruit Feather compatibility

* Same pinout as Adafruit Feather M0. An on-board component interfers with D5 (see note).
* MicroSD wired similar to Adalogger M0, but chip-select is on D7 not D4
* Voltage is 3.0 instead of 3.3
* I2C pull-ups are present

Note: If you don't need hardware handshaking on the GSM UART, the D5 pin can be freed up by cutting JP2 on the back of the board.


## Status

Testing in progress

## Credit

Design derived from Adafruit M0 Feather Proto and Adalogger

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
