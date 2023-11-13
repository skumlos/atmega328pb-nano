Arduino Mini Pro clone with Atmega328PB

This is basically an Arduino Mini Pro clone but with an Atmega328PB instead of Atmega328P.

Speed 16MHz and 5V.

The reasoning is to have the secondary I2C controller of the PB version, thus PE0 and PE1
pins are pulled to 2.54mm THT holes just like A4/A5 pins of the primary I2C controller.

Remember to burn a bootloader and fuses with a *real* programmer (like another Arduino
turned into an ISP). This requires you to connect to the ICSP pins, MOSI, MISO, SCK,
RESET, 5V and GND. I used a male pin header row  which I didn't solder but just held in
place during programming.

The design is tested and works, but it is hacked together pretty quick so bugs are possible.

(2023) Martin Hejnfelt, martin@hejnfelt.com


