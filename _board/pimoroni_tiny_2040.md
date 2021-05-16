
---
layout: download
board_id: "pimoroni_tiny_2040"
title: "Tiny 2040 Download"
name: "Tiny 2040"
manufacturer: "Pimoroni"
board_url: "https://shop.pimoroni.com/products/tiny-2040"
board_image: "pimoroni_tiny_2040.jpg"
date_added: 2020-5-16
downloads_display: true
download_instructions: "<url to install MicroPython on that board>"
mcu: "RP2040"
gpio: "12"
ram: "264"
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
  - RTC
  - Timer
  - WDT

features:
  - USB Host
  - SDCard
---

A postage stamp sized RP2040 development board with a USB-C connection and 8MB of flash, perfect for portable projects, wearables, and embedding into devices.


While we love the Raspberry Pi Pico we also wanted something smaller and with a bunch more flash on board. Introducing the Tiny 2040 - a teeny tiny powerhouse with the chops to realise truly ambitious projects.


Powered and programmable via USB-C, Tiny 2040 comes with 8MB of QSPI (XiP) flash on board so it can handle projects small and large with ease. The board is designed with castellated pads to allow it to be directly soldered onto a PCB or alternatively you can use pin headers to hook it up on a breadboard or directly with wires. We've even managed to fit in a programmable RGB LED, a reset button and some clever circuitry that lets you use the boot button as a user controllable switch.


It's compatible with firmware built for the Raspberry Pi Pico but offers a reduced number of pins due to its size. You can even run MicroPython on it!


**Features:**
* Powered by RP2040
* ARM Cortex M0+ running at up to 133Mhz
* 264kB of SRAM
* USB-C connector for power, programming, and data transfer
* 8MB of QSPI flash supporting XiP
* User controllable RGB LED
* Twelve IO pins (including four 12-bit ADC channels)
* Switch for basic input (doubles up as DFU select on boot)
* On-board 3V3 regulator
* Input voltage range 3V - 5.5V
* Dimensions: approx 22.9 x 18.2 x 6mm (L x W x H, including the USB-C port)


## Purchase
* [Tiny 2040](https://shop.pimoroni.com/products/tiny-2040) @ Pimoroni

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

