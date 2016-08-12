# FAR / Shitfaced Clowns Avionics Module

PCB files for Avionics Module

Derived from Adafruit M0 Proto and Adalogger

Compatible with Adafruit Feather products 
* Same pinout and format - all pins available
* MicroSD identical to Adalogger M0
* Voltage is 3.0 instead of 3.3
* Cut JP2 to free up D5

 All routed out pins are available for use by FeatherWing except D5. If you don't need hardware handshaking on the GSM UART, that pin also can be freed by cutting JP2 on the back of the board.    

Components:
* ATSAMD21G18
  * ARM Cortex-M0 at 32MHz
* MicroSD
* SIM868
  * GPS 
  * GSP/GPRS
* MPU-9250
  * 3D Acellerometer
  * 3D Gyroscope
  * 3D Magnetometer
* BMP180
  * Pressure
  * Temperature

# Status

UNTESTED

Currently sourcing PCB production and assembly

# Credit / License

Design derived from Adafruit M0 

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
