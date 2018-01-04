STM32F0..F (TSSOP20) Breakout Module
====================================

A breakout module for STM32F0 microcontrollers in TSSOP20 footprint.

Basic Features
--------------

Focus on small footprint and direct access to all pins.

Provides a 8 pin Micro-MaTch header for easy access to SWD and UART.

Pushbutton for Reset (press <1 second) and starting the bootloader (press >3 seconds).

Onboard LDO regulator (standard SOT-23-5) can be used for VDD and VDDA, just VDD or disabled completely.

Use of a crystal (SMT 3.2x2.5mm) is optional.

Options can be configured using solder bridges.

Power LED and User LED (on PA0, PF1 or disconnected).

Currently supported microcontrollers
------------------------------------

* STM32F030F4
* STM32F031F4
* STM32F031F6
* STM32F038F6
* STM32F042F4 (USB header must be connected externally)
* STM32F042F6 (USB header must be connected externally)
* STM32F070F6 (USB header must be connected externally)

Schematics & Layout
-------------------

Schematics & Layout were done in KiCAD.

[Schematics as PDF](https://github.com/electroniceel/stm32f0..f-breakout/raw/master/schematics.pdf)

Picture
-------

![Module and raw PCB](https://github.com/electroniceel/stm32f0..f-breakout/raw/master/pictures/board%2Bsample.jpg)

License
-------
![CC-BY](https://licensebuttons.net/l/by/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
