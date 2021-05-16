
---
layout: download
board_id: "adafruit_feather_rp2040"
title: "Adafruit Feather RP2040 Download"
name: "Adafruit Feather RP2040"
manufacturer: "Adafruit Industries"
board_url: "https://www.adafruit.com/product/4884"
board_image: "adafruit_feather_rp2040.jpg"
date_added: 2020-5-16
downloads_display: true
download_instructions: "https://micropython.org/download/rp2-pico/"
mcu: "RP2040"
gpio: "21"
ram: "256"
flash: "0"
ext_ram: "0"
ext_flash: "8192"

mcu_category: "RP2040"

machine_api:
  - Pin
  - ADC
  - PWM
  - UART
  - I2C
  - SPI
  - Timer
  - WDT

features:
  - Feather-Compatible
  - Battery Charging
  - USB Host
  - PIO (Programmable Input Ouput)
---
**Inside the RP2040 is a 'permanent ROM' USB UF2 bootloader**. What that means is when you want to program new firmware, you can hold down the BOOTSEL button while plugging it into USB (or pulling down the RUN/Reset pin to ground) and it will appear as a USB disk drive you can drag the firmware onto. Folks who have been using Adafruit products will find this very familiar - we use the technique on all our native-USB boards. Just note you don't double-click reset, instead hold down BOOTSEL during boot to enter the bootloader!


The **RP2040** is a powerful chip, which has the clock speed of Adafruit M4 (SAMD51). It does not have a floating point unit, or DSP hardware support, it will be done in software.


For peripherals, there are two I2C controllers, two SPI controllers, and two UARTs that are multiplexed across the GPIO - check the pinout for what pins can be set to which. There are 16 PWM channels, each pin has a channel it can be set to (ditto on the pinout).


The **RP2040** comes with the **PIO state machine** system which is a unique and powerful way to create custom hardware logic and data processing blocks that run on their own without taking up a CPU. For example, NeoPixels - often we bitbang the timing-specific protocol for these LEDs. For the RP2040, we instead use PIO object that reads in the data buffer and clocks out the right bitstream with perfect accuracy. Same with I2S audio in or out, LED matrix displays, 8-bit or SPI based TFTs, even VGA! In MicroPython you can create PIO control commands to script the peripheral and load it in at runtime. There are 2 PIO peripherals with 4 state machines each.


There is great C/C++ support for the RP2040, an Arduino support, an official MicroPython port, and a CircuitPython port! 


While the RP2040 has lots of onboard RAM (264KB), it does not have built-in FLASH memory. Instead, that is provided by the external QSPI flash chip. On this board there is 8 MB, which is shared between the program it's running and any file storage used by MicroPython. When using C/C++ you get the whole flash memory, if using Python you will have about 7 MB remaining for code, files, images, fonts, etc.


**Features:**
* Measures 50.8mm x 22.8mm x 7mm without headers soldered in
* Weight 5 grams
* RP2040 32-bit Cortex M0+ dual core running at ~125 MHz @ 3.3V logic and power
* 264 KB RAM
* 8 MB SPI FLASH chip for storing files and CircuitPython/MicroPython code storage. No EEPROM
* Tons of GPIO! 21 x GPIO pins with following capabilities:
  * Four 12 bit ADCs (one more than Pico)
  * Two I2C, Two SPI and two UART peripherals, we label one for the 'main' interface in standard Feather locations
  * 16 x PWM outputs - for servos, LEDs, etc
  * The 8 digital 'non-ADC/non-peripheral' GPIO are consecutive for maximum PIO compatibility
* Built in 200mA+ lipoly charger with charging status indicator LED
* Pin #13 red LED for general purpose blinking
* RGB NeoPixel for full color indication.
* On-board STEMMA QT connector that lets you quickly connect any Qwiic, STEMMA QT or Grove I2C devices with no soldering!
* Both Reset button and Bootloader select button for quick restarts (no unplugging-replugging to relaunch code)
* 3.3V Power/enable pin
* Optional SWD debug port can be soldered in for debug access
* 4 mounting holes
* 24 MHz crystal for perfect timing.
* 3.3V regulator with 500mA peak current output
* USB Type C connector lets you access built-in ROM USB bootloader and serial port debugging

## Purchase

* [Adafruit Feather RP2040](https://www.adafruit.com/product/4884) @ Adafruit Store

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

