
---
layout: download
board_id: "pycom_gpy"
title: "GPy - LTE CAT-M1/NB1 Download"
name: "GPy - LTE CAT-M1/NB1"
manufacturer: "Pycom"
board_url: "https://pycom.io/product/gpy/"
board_image: "pycom_gpy.jpg"
date_added: 2021-6-16
downloads_display: true
download_instructions: "https://pycom.io/product/gpy/"
mcu: "ESP32"
gpio: "22"
ram: "520"
flash: "0"
ext_ram: "4096"
ext_flash: "8192"

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
  - SDCard ?
  - SD ?

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Cellular LTE CAT-M1/NB1
  - Camera
  - USB Host
  - SDCard
---

The GPy is an ESP32 based MicroPython board fitted with a LTE communication capability. So GPy is a triple network development board.

Get on with a board that gets you into the available LTE CAT M1 / NB1 networks. The GPy gives you full flexibility during testing, install, deployment and is delivered RCM, IC, CE and FCC certified.

The GPy is our Micropython-programmable triple bearer. Different from its SiPy counterpart, the GPy offers WiFI, BLE and cellular CAT-M1/NB1. Create and connect your things everywhere.


Note:
* **The Cellular Antenna MUST always be used with LTE CAT M1 / NB1, or it could cause serious damage to the development board.**
* As of December 2019, **all our cellular products have been recalibrated** and screened on all 17 bands with a vastly improved RF test system to guarantee more stable connectivity, lower power consumption and faster network attachment. New specialised equipment and software from Rhode & Schwarz enables us to do more precise measurements during the calibration process. This enhances RF sensitivity and thus signal quality especially in areas with poor cellular coverage while reducing output power during transmit to improve battery performance.


**Features:**
* ESP32 based plateform
* Network processor handles the WiFi connectivity and the IPv6 stack
* WiFi (1 Km range) & BLE
* 512kB on-chip SRAM
* 8MB external Flash
* 4MB External RAM
* 24 GPIO pins (8 ADC inputs @ 12 bits, 2 DAC outputs @ 8 bits)
* Hardware floating point acceleration
* Python multi-threading
* Peripherals
  * 2x UARTs
  * 2x SPI
  * 1x I2C
  * I2S
  * micro SDCard
  * 2x Timer 64 bits (PWM capable over 16 channels)
  * RTC at 32 KHz
* Cellular Specification
  * One single chip for both CAT M1 and NB1
  * 3GPP release 13 LTE Advanced Pro
  * Supports narrowband LTE UE categories M1/NB1
  * Data rates: from 40 kbps to 375 kbps (see [board page](https://pycom.io/product/gpy/) for details)
* Security & Certifications
  * SSL/TLS support up to 1.2
  * WPA Enterprise security
  * AES encryption engine


## Purchase
* [Pycom, GPy board](https://pycom.io/product/gpy/)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

