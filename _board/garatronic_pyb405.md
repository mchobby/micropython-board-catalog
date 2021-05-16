---
layout: download
board_id: "garatronic_pyb405"
title: "Nadhat PYB405 Download"
name: "NadHat PYB405"
manufacturer: "Garatronic"
board_url: "https://shop.mchobby.be/en/micropython/1653-micropython-pyb405-hat-nadhat-3232100016538-garatronic.html"
board_image: "garatronic_pyb405.jpg"
date_added: 2020-5-12
downloads_display: true
download_instructions: "https://docs.garatronic.fr/pyb405.html"
mcu: "STM32F405RG"
gpio: "40"
ram: "192"
flash: "1024"
ext_ram: "0"
ext_flash: "0"

mcu_category: "STM32"

machine_api:
  - Pin
  - ADC
  - UART
  - I2C
  - SPI
  - RTC
  - Timer
  - WDT

features:
  - USB Host
  - SDCard
---

The PYB405 is like the MicroPython Pyboard (same microcontroller) but equipped with a Raspberry-Pi's GPIO (2x20-pin).

It works like any MicroPython and feature some interesting improvements. Everything learned from Pyboard can be applied to the PYB405.

The PYB405 has all the standard and quality equipement:
* STM32F405RG processor (as on the MicroPython Pyboard),
* A 3-axis accelerometer,
* A support for micro SD card,
* A user button, reset button and DFU button (to update the firmware)
* 4 color LEDs
* A battery for the RTC clock.
* A micro USB connector (for programming and access to the file system)
* A second micro USB connector (for power only).

__The Raspberry's GPIO__ is wired with Raspberry's standard pin functions (Pi 3 B+ definition) are all mapped to the corresponding function of the NADHAT PYB405. 

In addition, a jumper makes it possible to cross (or not) the RX/TX lines on the GPIO connector.

So you can use a Raspberry-Pi to control the PYB405 -OR- use the PYB405 to control some Raspberry-Pi HAT.


__MicroPython development on Raspberry-Pi:__

Use the NADHAT PYB405 board to make MicroPython developments from a Raspberry-Pi Zero or a Pi.  
This makes it possible to built a fully integrated MicroPython development environment, all you need to do is connect a monitor and a keyboard/mouse and let's go. In this case, the crossing of the RX/TX lines is indicated.  

In this case, the NADHAT PYB405 board becomes a powerful micro controller that can be dedicated to specific tasks and, in this way, support a Raspberry-Pi in its higher-level tasks.


__Exploiting HATs with MicroPython:__


Exposing a GPIO with Raspberry-Pi compatible functions is the opportunity to connect HATs on the NADHAT-PYB405 micro controller and with MicroPyhton. As the I2C, SPI and UART buses are well placed, it allows to exploit many HAT directly with the micro controller. As a result, the same HAT can be used in two different environments (on the Pi but also with the PYB405).  


__Make STM32 development with Raspberry-pi:__


Rather intended for advanced users, it is possible to prepare an OpenOCD development chaine on the Raspberry-Pi. This environment will download/upload and debug, from the Raspberry-Pi, the software developped for STM32. The Raspberry-Pi becomes a JTAG probe.
What's admirable in all this is that MicroPython itself is STM32 software and that, therefore, it becomes possible to debug it in SWD with a Raspberry-Pi :-)
Frédéric of Garatronic will certainly have the opportunity to write an article on this subject. 

All this is made possible because the nRst pin of the micro controller is connected to pin 15 (GPIO 22) of the Raspberry-Pi. This spoils the GPIO compatibility that allows a Raspberry-Pi to reset the MicroPython board (a necessary evil for doing OpenOCD development). 


**Features:**
* STM32F405RG microcontoler (same as Pyboard),
* 3-axis accelerometer,
* microSD card connector,
* user button, reset button and DFU button (to update the firmware)
* 4 color LEDs
* A battery for RTC clock.
* A micro USB connector (for programing and access to the file system)
* A second micro USB connector (for power only).
* pHat form factor (like the Pi Zero).
* 40-pin GPIO, with advanced compatibility with the Raspberry-Pi.
* Extra CN2 connector


## Purchase
Add any manufacturer links to purchase the board
* [Garatronic, PYB405](https://shop.mchobby.be/en/micropython/1653-micropython-pyb405-hat-nadhat-3232100016538-garatronic.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

