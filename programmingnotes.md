# Programming notes
[DC801](https://dc801.org/) and [theTransistor](http://thetransistor.com/) bring you yet another fun party badge.

##Progamming the Propeller
- [Parallax Propeller mCU](https://www.parallax.com/product/p8x32a-d40)
- 1) Plug in your USB and slide the bottom switch to the left to select the Propeller Chip
- 2) Use your favorite Propeller Tool to program the chip.
NOTE: Make sure you have selected "RTS" as the Propeller Reset Signal (see image below)
![Defcon VIP Party Badge 2015](/images/propellertoolsettings.png)

##Programing the Atmega328 Arduino
The Atmel 328P comes preloaded with the Arduino Bootloader. It sets up an SPI communication link between some of the IO (like the analog sticks) and the Propeller.
- 1) Plug in your USB and slide the bottom switch to the right to select the 328P
- 2) Use your favorite Arduino Programming Tool to program the chip.

##Flashing the Arduino Bootloader / Direct Atmel Programming
This is a little more advanced, and requires you to remove the Propeller chip from its socket. Please review the schematics if you wish to program the 329P directly.
