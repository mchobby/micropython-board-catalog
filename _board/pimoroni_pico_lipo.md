
---
layout: download
board_id: "pimoroni_pico_lipo"
title: "pimoroni_pico_lipo Download"
name: "Pimoroni Pico Lipo"
manufacturer: "Pimoroni"
board_url: "https://shop.pimoroni.com/products/pimoroni-pico-lipo"
board_image: "pimoroni_pico_lipo.jpg"
date_added: 2020-5-16
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
  - RTC
  - Timer
  - WDT


features:
  - Pico-Compatible
  - Battery Charging
  - USB Host
  - SDCard
  - Qwiic / StemmaQT
---

RP2040-powered microcontroller with lots of flash memory, USB-C, STEMMA QT/Qwiic and debug connectors... and built in LiPo charging!


Pimoroni Pico LiPo is powered and programmable via USB-C and comes with a mighty 16MB of QSPI (XiP) flash on board to take on the chunkiest of projects (we'll also have a 4MB version available soon). We've made it super easy to connect to things solderlessly too - there's a Qwiic/STEMMA QT connector so you can hook up a whole host of different sensors and breakouts, and a debug connector for if you want to do your programming using a SWD debugger. Because we love buttons at Pirate HQ, there's an on/off button and a BOOTSEL button, which can also be used as a user switch.


Pimoroni Pico LiPo also has onboard LiPo/LiIon battery management - the inbuilt charging circuitry means charging your battery is as easy as plugging your Pimoroni Pico Lipo in via USB. There's two indicator LEDs connected to the battery circuit to keep you informed of on/off state and charging status and it's compatible with any of our LiPo, LiIon and high capacity LiPo batteries.

Programmable with C++, MicroPython or CircuitPython, Pimoroni Pico LiPo is the perfect powerhouse for your portable projects. 


**Features:**

* Powered by RP2040
* Dual ARM Cortex M0+ running at up to 133Mhz
* 264kB of SRAM
* 4MB/16MB of QSPI flash supporting XiP
* MCP73831 charger with 215mA charging current (datasheet)
* XB6096I2S battery protector (datasheet)
* USB-C connector for power, programming, and data transfer
* 4 pin Qw-ST (Qwiic / STEMMA QT) connector
* 3 pin debug connector (JST-SH)
* 2-pole JST PH battery connector, with polarity marked on the board
* Switch for basic input (doubles up as DFU select on boot)
* Power button
* Power, charging and user LED indicators
* On-board 3V3 regulator (max regulator current output 600mA)
* Input voltage range 3V - 5.5V
* Compatible with Raspberry Pi Pico add-ons
* Measurements: approx 53mm x 21mm x 8mm (L x W x H, including connectors)


## Purchase
* [Pimoroni Pico LiPo](https://shop.pimoroni.com/products/pimoroni-pico-lipo)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

