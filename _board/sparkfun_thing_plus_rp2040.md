
---
layout: download
board_id: "sparkfun_thing_plus_rp2040"
title: "Thing Plus RP2040 Download"
name: "SparkFun Thing Plus - RP2040"
manufacturer: "SparkFun"
board_url: "https://www.sparkfun.com/products/17745"
board_image: "sparkfun_thing_plus_rp2040.jpg"
date_added: 2020-5-16
downloads_display: true
download_instructions: "https://micropython.org/download/rp2-pico/"
mcu: "RP2040"
gpio: "18"
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
  - RTC
  - Timer
  - WDT

features:
  - Feather-Compatible
  - Battery Charging
  - USB Host
  - Qwiic / StemmaQT
  - PIO
---

The SparkFun Thing Plus - RP2040 is a low-cost, high performance board with flexible digital interfaces featuring the Raspberry Pi Foundation's **RP2040 microcontroller**. Besides the **Thing Plus or Feather footprint** (with 18 GPIO pins), the board also includes an SD card slot, 16MB (128Mbit) flash memory, a JST single cell battery connector (with a charging circuit and fuel gauge sensor), an **addressable WS2812 RGB LED**, JTAG PTH pins, four (4-40 screw) mounting holes, and our signature **Qwiic connector**.


The RP2040 contains two ARM Cortex-M0+ processors (up to 133MHz) and features:
* 264kB of embedded SRAM in six banks
* 6 dedicated IO for SPI Flash (supporting XIP)
* 30 multifunction GPIO (only a part of it is availables):
  * Dedicated hardware for commonly used peripherals
  * Programmable IO for extended peripheral support
  * Four 12-bit ADC channels with internal temperature sensor (up to 0.5 MSa/s)
* USB 1.1 Host/Device functionality


The RP2040 is supported with both C/C++ and MicroPython cross-platform development environments, including easy access to runtime debugging. It has UF2 boot and floating-point routines baked into the chip. While the chip has a large amount of internal RAM, the board includes an additional 16MB of external QSPI flash memory to store program code.

**Features:**

* Raspberry Pi Foundation's RP2040 microcontroller
* 16MB QSPI Flash Memory
* JTAG PTH Pins
* Thing Plus (or Feather) Form-Factor
* 18x Multifunctional GPIO Pins
  * Four available 12-bit ADC channels with internal temperature sensor (500kSa/s)
  * Up to eight 2-channel PWM
  * Up to two UARTs
  * Up to two I2C buses
  * Up to two SPI buses
* USB-C Connector: USB 1.1 Host/Device functionality
* 2-pin JST Connector for a LiPo Battery (not included): 500mA charging circuit
* Qwiic Connector
* Buttons: Boot, Reset
* LEDs: 
  * Red 3.3V power indicator,
  * Yellow battery charging indicator
  * Blue status/test LED (GPIO 25)
  * WS2812 - Addressable RGB LED (GPIO 08)
* Four Mounting Holes
* Dimensions: 58.4mm x 22.8mm


## Purchase
* [SparkFun Thing Plus RP2040](https://www.sparkfun.com/products/17745)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

