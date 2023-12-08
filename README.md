# Hitachi-HD44780-LCD

The Hitachi HD44780 LCD module is well-known not only in the hobbyist and small business but also in the professional industry, which uses these displays in machine/man interfaces like printers, telephones, uninterruptible power supplies, diesel generators, and other industrial equipment.

This LCD is cheap, easy to use, and it comes in a few number of size configurations: 8×1 (one row of eight characters), 16×2, 20×2, 20×4…

For this project, I am going to use a simple library called [LiquidCrystal](http://arduino.cc/en/Reference/LiquidCrystal). But don't worry, this library is included in the standard package of Arduino 1.0.10 (or later).

For this project you need:
- Arduino Nano 3.0
- Hitachi HD44780 LCD module
- 10kOhm trimmer (to regulate the LCD contrast)
- Breadboard and wires

Now you have to replicate the circuit below:

![alt text](resources/Hitachi-HD44780-LCD_bb.png?raw=true)

Upload the [code](Hitachi_HD44780.ino) to the board.

For more information about this library, you can read the official Arduino's [LiquidCrystal](http://arduino.cc/en/Reference/LiquidCrystal) tutorial, where you can find more useful functions and examples.