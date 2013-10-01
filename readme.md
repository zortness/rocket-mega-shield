Rocket Mega Shield Revision 2
=============================

![rendering](https://raw.github.com/zortness/rocket-mega-shield/master/render/rev2.1/board.png)
![rendering](https://raw.github.com/zortness/rocket-mega-shield/master/render/rev2.1/board_fill.png)
![rendering](https://raw.github.com/zortness/rocket-mega-shield/master/render/rev2.1/schematic.png)

These are the Eagle files for an Arduino Mega shield with sensors and features needed by aviation and rocketry enthusiasts. 
The board is also designed to be extremely easy to use for any hobbyist application. 

These files are released under the [Creative Commons Attribution-ShareAlike](http://creativecommons.org/licenses/by-sa/3.0/) license. 
You're free to use and modify them for any purpose, including commercial.

These files make use of footprints taken from the [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library) 
and [Sparkfun Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries). 

My library of modified parts is [available here](https://github.com/zortness/zort-eagle-library).


Concept
--------
This shield is geared toward aviation purposes, specifically rocketry. The board itself does not dictate how it is used.
It can also be used for things like planes, boats, cars, or robotics, though this might be overkill for those purposes.


Features
--------
* Supports 5V and 3.3V boards (Mega or Due)
* Supports MicroSD cards that can operate in SPI mode
* Supports all XBee models, using UART Serial for communication
* -- User selectable XBee on UART0 or UART1 via switch
* -- Tie-down holes included in layout
* 10Hz GPS tied to UART2
* -- External GPS Antenna u.FL connector
* High Sensitivity BMP180 Altimeter (barometric pressure and temperature)
* Full 9-degrees-of-freedom capabilities
* -- 3-Axis 16G accelerometer and magnometer (LSM303DLHCTR)
* -- 3-Axis 8-gauss gyroscope (L3GD20TR)
* 3-Axis 200G accelerometer for high-force calculations (ADXL377)
* External reverse-polarity-protected power supply via JST2 connector
* -- Will also power the Arduino
* -- Can also be powered by the Arduino over USB
* -- Up to 18V
* Input voltage measuring at ~1:6 scale
* 4x high-amp MOSFETs with continuity detection
* -- Designed for rocket deployment pyrotechnics
* Automatic level-shifting for sensors (up to 5V)
* Buzzer for making loud noises
* -- MOSFET controlled, attached to PWM pin 8
* Lots of pretty flashing lights

See the [Bill of Materials](https://github.com/zortness/rocket-mega-shield/blob/master/bom.md)
and [parts manifest](https://github.com/zortness/rocket-mega-shield/blob/master/manifest.txt)
for more information.


Versions
--------
* RocketMega Revision 2.1 - Third prototype, only pin and routing changes from R2 for Due compatability
* RocketMega Revision 2 - Second prototype board, intended for wider production, August 2013
* RocketDuino Revision 1 - Initial prototype board, June 2013 


Prototype Images
----------------
Revision 2

![R2](https://raw.github.com/zortness/rocket-mega-shield/master/render/rev2/r2.jpg)


Revision 1

![R1_a](https://raw.github.com/zortness/rocket-mega-shield/master/render/v1/v1_1.jpg)
![R1_b](https://raw.github.com/zortness/rocket-mega-shield/master/render/v1/v1_2.jpg)
