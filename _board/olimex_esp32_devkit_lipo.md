
---
layout: download
board_id: "olimex_esp32_devkit_lipo"
title: "ESP32-DevKit-LiPo Download"
name: "ESP32-DevKit-LiPo : ESP32 WiFi/BLE Development board"
manufacturer: "Olimex"
board_url: "https://www.olimex.com/Products/IoT/ESP32/ESP32-DevKit-LiPo/open-source-hardware"
board_image: "olimex_esp32_devkit_lipo.jpg"
date_added: 2021-5-20
downloads_display: true
download_instructions: "http://micropython.org/download/esp32/"
mcu: "ESP-WROOM-32"
gpio: "30"
ram: "520"
flash: "0"
ext_ram: "0"
ext_flash: "4096"

mcu_category: "ESP32"

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
  - Wi-Fi
  - Bluetooth/BTLE
  - Battery Charging
  - USB Host
---

This board is pin to pin compatible with Espressif ESP32-CoreBoard (ESP32-DevKitC), but adds Lipo charger and ability to work on LiPo power when external power supply is missing, allowing handheld applications.

All components used are with industrial grade oprating temperature -40 to +85C.

__Do not forget to press the USER button when power-up to activate FLASH mode__.

**Features:**
* ESP32-WROOM-32 WiFi/BLE module
* User button
* Micro USB connector
* Built-in USB-Serial programmer
* Built-in LiPo charger
* LiPo battery connector
* PCB dimensions: 48 x 28 mm
* Operating temperature: -40 to +85C


## Purchase
* [ESP32-DevKit-LiPo board](https://www.olimex.com/Products/IoT/ESP32/ESP32-DevKit-LiPo/open-source-hardware)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

