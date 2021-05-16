
---
layout: download
board_id: "<board id, EG: garatronic_pybstick26std>"
title: "<board name, EG: PYBStick 26 Standard> Download"
name: "<board name, EG: PYBStick 26 Standard>"
manufacturer: "<board manufacturer, EG: Garatronic>"
board_url: "<url to board details + documentation>"
board_image: "shortname.jpg, EG: garatronic_pybstick26std.jpg"
date_added: 2020-3-31
downloads_display: true
download_instructions: "<url to install MicroPython on that board>"
mcu: "MCU identification, EG: STM32F411RE"
gpio: "Number of GPIOs accessibles on board. EG: 8"
ram: "MCU RAM in Kb: EG: 128"
flash: "Internal MCU Flash in Kb, EG: 512"
ext_ram: "External RAM in Kb: EG: 4096"
ext_flash: "External RAM in Kb: EG: 4096"

mcu_category: "One of the following values... then remove the list"
  - STM32
  - SAMD21
  - SAMD51
  - RP2040
  - ESP32
  - ESP8266
  - RISC-V

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
  - SDCard

features:
  - Feather-Compatible
  - Microbit-Compatible
  - Display
  - Wi-Fi
  - Bluetooth/BTLE
  - Robotics
  - LoRa/Radio
  - Battery Charging
  - GPS
  - Camera
  - USB Host
  - SDCard
---

The board description should be written to inform a what makes the board unique and link to relevant info about it.


Start any new section of text by preceding it with 2 empty lines.


**Highlight section of text** by starting it with double star section. 


**Features:**
Do not forget to insert summary with plateform features like the following (no text, just list).
* Single core @ 133MHz
* 264kB on-chip SRAM
* 8MB external QSPI Flash
* 30 GPIO pins (4 ADC inputs)
* Peripherals
  * 1x UARTs
  * 2x I2C controllers
  * 8x PWM channels
  * USB 1.1 controller

## Purchase
Add any manufacturer links to purchase the board
* [Manufacturer, EG:Garatronic](https://link_to_the_product)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

