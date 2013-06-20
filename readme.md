Rocket Mega Shield
==================

![rendering](https://raw.github.com/zortness/rocket-mega-shield/master/render/v1/board_v1.png)

These are the Eagle files for an Arduino Mega shield with sensors and features targeting rocketry enthusiasts.

These files are released under the [Creative Commons Attribution-ShareAlike](http://creativecommons.org/licenses/by-sa/3.0/) license. 
You're free to use and modify them for any purpose, including commercial.

These files make use of footprints taken from the [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library) 
and [Sparkfun Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries). 

My library of modified parts will be available shortly (just cleaning it up).


Concept
--------
This shield is geared toward aviation purposes, specifically rocketry. The board itself does not dictate how it is used.
It can also be used for things like planes, boats, cars, or robotics, though this might be overkill for those purposes.


Features
--------
* Supports MicroSD cards that can operate in SPI mode. 
* Supports all XBee models, using UART Serial for communication.
* User selectable XBee on TX0/RX0 or TX1/RX1 via switch
* User selectable GPS on TX1/RX1 or TX2/RX2 via switch
* User selectable 3.3V/5V output scale for analog 55G accelerometer (for Arduino Due)
* External power supply (non-Arduino)
* Automatic switching between board power (for debugging) and external power (for use)
* Two solid-state relays and outputs with screw terminals, connected to external power supply (intended for dual deployment)
* Automatic level-shifting for I2C sensors (for Arduino Mega)
* Hopefully doesn't suck


Sensors
--------
* 66 channel 10Hz GPS [FGPMMOPA6H](http://www.adafruit.com/products/790)
* Barometric Pressure / Temperature Sensor (Altimeter) [Bosch BMP085](http://www.digikey.com/product-detail/en/BMP085/828-1005-1-ND/1987010)
* 3-axis Gyroscope [ST Microelectronics L3GD20TR](http://www.digikey.com/product-detail/en/L3GD20TR/497-12081-1-ND/2793125)
* 3-axis 16G Accelerometer [ST Microelectronics LSM303DLHCTR](http://www.digikey.com/product-detail/en/LSM303DLHCTR/497-11918-1-ND/2757636)
* 2-axis 55G Analog Accelerometer [Analog Devices AD22285-R2](http://www.digikey.com/product-detail/en/AD22285-R2/AD22285-R2CT-ND/774192)


Versions
--------
* RocketDuino V1 - Initial prototype board, June 2013 
(download [zip](https://github.com/zortness/rocket-mega-shield/archive/v1.zip) or [tar.gz](https://github.com/zortness/rocket-mega-shield/archive/v1.tar.gz))