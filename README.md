# TecDev-PIC18F6490-Development-Board

![TecDev-PIC18F6490](https://github.com/Tecfield-SIA/TecDev-PIC18F6490-Development-Board/blob/main/Images/PIC18F6490.gif)

________________________________________

## Overview

TecDev-PIC18F6490 is a development board designed to fully explore the capabilities of the PIC18F6490 microcontroller. This board is part of the TecDev series, following a unique design language that enhances usability and aesthetics.

The primary goal of this board is to provide an efficient and practical platform for testing, debugging, and designing projects with the PIC18F6490, making it easier for engineers and hobbyists to integrate this microcontroller into their applications.

__A Unique Challenge & Experience__

This board holds a special place for me as it was my first experience working with PIC microcontrollers. Unlike other platforms where extensive schematics and references are available, designing this board relied solely on studying Microchip's datasheet, repeatedly reading and analyzing every detail to create a stable and optimized circuit. This journey was both challenging and deeply rewarding.

Another unique aspect of this board is its sustainability factor—the microcontroller used in this design was a salvaged PIC18F6490, giving it a new purpose and a second life. I believe in maximizing the potential of components rather than letting them go to waste, making this project even more meaningful.

________________________________________

## Features

- PIC18F6490 Microcontroller
- Dual voltage operation (5V & 3.3V) selectable via a toggle switch
- Multiple user-accessible peripherals:
  - 1x LED (connected via MOSFET to RD2)
  - 1x Push Button (connected to RD1)
  - 2x Addressable RGB LEDs (connected to RD0)
- Full GPIO exposure:
  - All microcontroller pins are accessible via well-labeled headers
-	Dedicated programming headers (compatible with PICkit, using yellow headers for easy identification)
-	USB-C power input, with an option to power via a PICkit programmer
-	SPI/I2C Mode Switching:
  - A toggle switch allows easy switching between SPI (SDI, SCK) and I2C (SDA, SCL with 4.7kΩ pull-ups)
-	16MHz Main Crystal and 32kHz RTC Crystal
-	Onboard Voltage Regulation:
  -	AMS1117 (3.3V, 1A max)
  -	Zener diode protection (5.6V) for voltage safety
-	Power Indicators: Separate LEDs for 3.3V and 5V power rails

________________________________________

## Usage & Applications

-	Microcontroller feature testing before implementing in larger projects
-	Developing and debugging firmware for the PIC18F6490
-	Rapid prototyping for embedded systems
-	Educational tool for learning and experimenting with PIC microcontrollers

________________________________________

## Getting Started

1.	Powering the Board: Use the USB-C port or a PICkit programmer (selectable via a switch).
2.	Programming: Utilize the PICkit programmer via the dedicated yellow pin headers.
3.	Using Peripherals: Interact with the onboard LED, button, and addressable RGB LEDs for basic functionality tests and debugging assistance.
4.	I2C/SPI Selection: Use the toggle switch to select between SPI and I2C modes.

![TecDev-PIC18F6490](https://github.com/Tecfield-SIA/TecDev-PIC18F6490-Development-Board/blob/main/Images/1.jpg)

________________________________________

## Final Thoughts

Building this board was an exciting and insightful experience, pushing my skills in circuit design and firmware development. Whether you're an embedded engineer, a hobbyist, or just someone curious about PIC microcontrollers, I hope this board helps you in your projects as much as it helped me in my learning journey.

Feel free to explore, contribute, and share your feedback!

__Contact__

For questions or discussions, feel free to open an issue or reach out via LinkedIn or email me at Tecfield@live.com.
www.linkedin.com/in/siavash-alizadeh-tecfield
