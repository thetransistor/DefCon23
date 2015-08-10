# DC801 2015 Pinout
Pinouts for the DC801 Electronic VIP Party Badge for Defcon 2015 for kids who can't read good and wanna learn to do other stuff good too


##Propeller IO Pinout
Propeller IO | LCD Pin
-------------|--------------
P0  | D2
P1  | D3
P2  | D4
P3  | D5
P4  | D6
P5  | D7
P6  | D0
P7  | D1
P11 | RST
P12 | CS
P13 | RS
P14 | RW
P15 | RD

Propeller IO | SD Card
-------------|--------------
P20 | SCK
P21 | DO
P22 | DI
P23 | SS

Propeller IO | RGB LEDS
-------------|--------------
P26 | Data

Propeller IO | XBee Socket
-------------|--------------
P8  | DOUT
P9  | DIN
P10 | RST

Propeller IO | WiFi
-------------|--------------
P24 | RX
P25 | TX
P27 | RST

Propeller IO | EEPROM
-------------|--------------
P28 | SCL
P29 | SDA

Propeller IO | PROP Serial
-------------|--------------
P30 | TX
P31 | RX

Propeller IO | Atmega 328P Arduino
-------------|--------------
P16 | D13 (SCK)
P17 | D12 (MISO)
P18 | D11 (MOSI)
P19 | D10 (CS)

##Atmega328P IO Pinout
328P | Arduino IO | Rotary Encoder
-----|------------|--------------
32 | D2 | Encoder 1
1  | D3 | Encoder 2

328P | Arduino IO | Buttons
-----|------------|--------------
2  | D4 | Button A
9  | D5 | Button B
10 | D6 | RightJoy Button
11 | D7 | LeftJoy Button

328P | Arduino IO | Joystick 
-----|------------|--------------
23 | A0 | LeftJoy X-Axis
24 | A1 | LeftJoy Y-Axis
25 | A2 | RightJoy X-Axis
26 | A3 | RightJoy Y-Axis

328P | Arduino IO | Propeller Link
-----|------------|--------------
14 | D10 | P19 (CS)
15 | D11 | P18 (MOSI)
16 | D12 | P17 (MISO)
17 | D13 | P16 (SCK)

328P | Arduino IO | Misc
-----|------------|--------------
27 | A4 | LCD Backlight Control
12 | D8 | Battery Stat 1
13 | D9 | Battery Stat 2
22 | A7 | Battery Voltage
30 | RX | Arduino RX
31 | TX | Arduino TX

328P | Arduino IO | Extra IO
-----|------------|--------------
19 | A6 | Extra IO 1
28 | A5 | Extra IO 2








