# IVT (IV-TINY) - A FORTH-programable Scientific RPN Calculator that fits in 8 kilobytes (Arduino, ATTINY85)


## ** IVT IS COMING SOON! **

![ivt](https://user-images.githubusercontent.com/16148023/107773107-7519f480-6d3d-11eb-83c8-1f47c9d18439.jpg)

See a short video of IVEE at: https://youtu.be/VqkXdZuKv6A

IVT is the smallest member of the IV-calculator series (FORTH-like programable calculators). The name IV stands for the roman number 4, which was the basis for naming FORTH (4th generation programming language).

The hardware is simple:
* AVR ATTINY85 microcontroller (8192/512/512 bytes of FLASH/RAM/EEPROM)
* OLED-display (128c32, I2C, SSD1306)
* 16 keys touch sensitive keypad (TTP229-BSF, 2 wire)
* CR2032 battery

IVT was made without compromises to offer a complete FORTH-like programming environment and a maximum of mathematical functions (mostly written in FORTH itself).
And it's amazing how much calculating power fits into 8 kilobytes:
* 79 intrinsic functions based on FORTH
* A wide range of mathematical and scientific commands (DUP DROP SWAP ROT OVER / * - + PI SQRT POWER INV INT EXP LN SIN COS TAN ASIN ACOS ATAN GAMMA P>R R>P)
* Statistics, line best fit and normal distribution (CDF, PDF)
* Present value calculations
* Programming: Up to 16 user definable programs with a total of 440 steps (< = <> > IF ELSE THEN BEGIN UNTIL)
* A solver to find roots of user defined functions
* A dictionary of all commands, words and programs
* A use definable menu for fast access to all commands, words and programs
* Save up to 10 numbers/constants permanently

Have fun!
deetee
