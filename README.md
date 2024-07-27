# TeensyRA8876-SPI
A RA8876 library for use with SPI driver for Teensy boards and variants.

# PINOUTS
## WIRED
*** CONNECTING THE TEENSY TO THE ER-TFTM101-1 in SPI mode ***

40 pin dual inline connector pinouts can be found here.
https://www.buydisplay.com/download/interfacing/ER-TFTM101-1_RTP_Interfacing.pdf

TEENSY 36/40/41,MicroMod         ER-TFTM101-1
-------------------------------------------------------------
- Pin 10 /CS                       Pin 5  /SCS
- Pin 13 SCK                       Pin 8  SCLK
- Pin 11 MOSI                      Pin 7  SDI
- Pin 12 MISO                      Pin 6  SDO
- Pin 21 RESET                     Pin 11 /RESET
- Pin 20 BLITE                     Pin 14 BL_CONTROL (VDD 3.3V)
-------------------------------------------------------------

This is WIP. More to come.
