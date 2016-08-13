# FAR / Shitfaced Clowns Avionics Module

PCB files for Avionics Module


# Components/Features 

* Adafruit Feather-compatible
* ATSAMD21G18
  * ARM Cortex-M0 at 32MHz
* MicroSD
* SIM868
  * GPS positioning
  * GSM/GPRS (nanoSIM)
* MPU-9250
  * 3D Acellerometer
  * 3D Gyroscope
  * 3D Magnetometer
* BMP280
  * Pressure
  * Temperature


# Adafruit Feather compatibility

* Same pinout as Adafruit Feather M0. An on-board component interfers with D5 (see note).
* MicroSD wired similar to Adalogger M0, but chip-select is on D7 not D4
* Voltage is 3.0 instead of 3.3
* I2C pull-ups are present

Note: If you don't need hardware handshaking on the GSM UART, the D5 pin can be freed up by cutting JP2 on the back of the board.


# Status

UNTESTED

Currently sourcing PCB production and assembly

# Credit

Design derived from Adafruit M0 Feather Proto and Adalogger

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
