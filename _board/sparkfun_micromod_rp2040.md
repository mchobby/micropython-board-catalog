
---
layout: download
board_id: "sparkfun_micromod_rp2040"
title: "SparkFun MicroMod RP2040 Processor> Download"
name: "SparkFun MicroMod RP2040 Processor"
manufacturer: "Sparkfun"
board_url: "https://www.sparkfun.com/products/17720"
board_image: "sparkfun_micromod_rp2040.jpg"
date_added: 2021-4-16
downloads_display: true
download_instructions: "https://micropython.org/download/rp2-pico/"
mcu: "RP2040"
gpio: "30"
ram: "264"
flash: "0"
ext_ram: "0"
ext_flash: "16384"

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
  - M.2 connectorFeather-Compatible
---

The SparkFun MicroMod Pi RP2040 Processor Board is a low-cost, high-performance board with flexible digital interfaces featuring the Raspberry Pi Foundation's RP2040 microcontroller. With the MicroMod M.2 connector, connecting your MicroMod Pi RP2040 Processor Board to one of the [MicroMod carrier board](https://www.sparkfun.com/search/results?term=MicroMod). Simply match up the key on your processor's beveled edge connector to the key on the M.2 connector and secure it with a screw (included with all Carrier Boards).

The RP2040 utilizes dual ARM Cortex-M0+ processors (up to 133MHz):
* 264kB of embedded SRAM in six banks
* 6 dedicated IO for SPI Flash (supporting XIP)
* 30 multifunction GPIO:
  * Dedicated hardware for commonly used peripherals
  * Programmable IO for extended peripheral support
  * Four 12-bit ADC channels with internal temperature sensor (up to 0.5 MSa/s)
* USB 1.1 Host/Device functionality

The RP2040 is supported with both C/C++ and MicroPython cross-platform development environments, including easy access to runtime debugging. It has UF2 boot and floating-point routines baked into the chip. The built-in USB can act as both device and host. It has two symmetric cores and high internal bandwidth, making it useful for signal processing and video. While the chip has a large amount of internal RAM, the board includes an additional external flash chip.


**Features:**
* Dual Cortex M0+ processors, up to 133 MHz
* 264 kB of embedded SRAM in 6 banks
* 6 dedicated IO for QSPI flash, supporting execute in place (XIP)
* 30 programmable IO for extended peripheral support
* SWD interface
* Timer with 4 alarms
* Real time counter (RTC)
* USB 1.1 Host/Device functionality
* Supported programming languages: MicroPython, C/C++
* Specific peripheral made available on MicroMod
  * 1x USB dedicated for programming and debug (Host capable)
  * 2x UARTs
  * 2x I2C
  * 2x SPI
  * 29x GPIO
  * 2x Digital Pins
  * 3x Analog Pins
  * 16x PWM
  * 128Mbit/16MB (external) flash memory
  * Status LED
  * VIN Level ADC


## Purchase
* [SparkFun MicroMod RP2040 Processor](https://www.sparkfun.com/products/17720) @ SparkFun

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

