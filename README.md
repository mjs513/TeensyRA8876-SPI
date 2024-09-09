# TeensyRA8876-SPI
A RA8876 library for use with SPI driver for Teensy boards and variants.

Communication with the Teensy is accomplished using SPI. To install unzip the zip file in the Arduino/libraries folder.

Example sketches can be found in the TeensyRA8876-8080 and TeensyRA8876-SPI examples folders.

*** CONNECTING THE TEENSY TO THE ER-TFTM101-1 in SPI mode ***

40 pin dual inline connector pinouts can be found here.

https://www.buydisplay.com/download/interfacing/ER-TFTM101-1_CTP_Interfacing.pdf

# PINOUTS
## WIRED
TEENSY/DEV BOARD <______________> ER-TFTM101-1
-------------------------------------------------------------
- Pin 10 /CS <___________________> Pin 5  /SCS
- Pin 13 SCK <___________________> Pin 8  SCLK
- Pin 11 MOSI <__________________> Pin 7  SDI
- Pin 12 MISO <__________________> Pin 6  SDO
- Pin 21 RST <___________________> Pin 11 /RESET
- Pin 20 BACKLITE <______________> Pin 14 BL_CONTROL (VDD 3.3V)
-------------------------------------------------------------

# This is WIP. More to come.
