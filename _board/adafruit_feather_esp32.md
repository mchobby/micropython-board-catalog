
---
layout: download
board_id: "adafruit_feather_esp32"
title: "Adafruit HUZZAH32 – ESP32 Feather Board Download"
name: "Adafruit HUZZAH32 – ESP32 Feather Board"
manufacturer: "Adafruit"
board_url: "https://www.adafruit.com/product/3405"
board_image: "adafruit_feather_esp32.jpg"
date_added: 2020-5-17
downloads_display: true
download_instructions: "http://micropython.org/download/esp32/"
mcu: "ESP-WROOM-32"
gpio: "21"
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
  - Feather-Compatible
  - Wi-Fi
  - Bluetooth/BTLE
  - Battery Charging
  - USB Host
---

It is ESP32-based Feather, made with the official WROOM32 module. As any Feather this board is fitted with USB-to-Serial converter, automatic bootloader reset, Lithium Ion/Polymer charger, and all of the GPIOs brought out so you can use it with any of the [FeatherWing EcoSystem](https://www.adafruit.com/category/777). 


The ESP32 module contains a dual-core ESP32 chip, 4 MB of SPI Flash, tuned antenna, and all the passives you need to take advantage of this powerful processor. The ESP32 has both WiFi and Bluetooth Classic/LE support. That means it's good for wireless or Internet-connected project.


The ESP32 is a perfect upgrade from the ESP8266 that has been so popular. In comparison, the ESP32 has more GPIO, plenty of analog inputs, two analog outputs, multiple extra peripherals (like a spare UART), two cores so you don't have to yield to the WiFi manager, much higher-speed processor.

**Features:**
* 240 MHz dual core Tensilica LX6 microcontroller with 600 DMIPS
* Integrated 520 KB SRAM
* Integrated 802.11b/g/n HT40 Wi-Fi transceiver, baseband, stack and LWIP
* Integrated dual mode Bluetooth (classic and BLE)
* 4 MByte flash include in the WROOM32 module
* On-board PCB antenna
* Ultra-low noise analog amplifier
* Hall sensor
* 10x capacitive touch interface
* 32 kHz crystal oscillator
* 3x UARTs (only two are configured by default in the Feather Arduino IDE support, one UART is used for bootloading/debug)
* 3x SPI (only one is configured by default in the Feather Arduino IDE support)
* 2x I2C (only one is configured by default in the Feather Arduino IDE support)
* 12x ADC input channels
* 2x I2S Audio
* 2x DAC
* PWM/timer input/output available on every GPIO pin
* OpenOCD debug interface with 32 kB TRAX buffer
* SDIO master/slave 50 MHz
* SD-card interface support

## Purchase
* [Adafruit HUZZAH32 – ESP32 Feather Board](https://www.adafruit.com/product/3405)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

