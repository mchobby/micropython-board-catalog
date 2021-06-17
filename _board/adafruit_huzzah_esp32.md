
---
layout: download
board_id: "adafruit_huzzah_esp32"
title: "Adafruit HUZZAH32 – ESP32 Breakout Download"
name: "Adafruit HUZZAH32 – ESP32 Breakout Board"
manufacturer: "Adafruit"
board_url: "https://www.adafruit.com/product/4172"
board_image: "adafruit_huzzah_esp32.jpg"
date_added: 2021-5-17
downloads_display: true
download_instructions: "http://micropython.org/download/esp32/"
mcu: "ESP32-WROOM-32E"
gpio: "26"
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
---

This breakout is basically the 'big sister' of the HUZZAH ESP8266, but fitted with an ESP32! This breakout just get a regulator, some protection diodes, two buttons and an LED. For some projects, where price and size are at a premium, you can program this board over the 'FTDI cable' breakout when needed, and leave it alone otherwise.


That module in the middle of the breakout contains a dual-core ESP32 chip, 4 MB of SPI Flash, tuned antenna, and all the passives you need to take advantage of this powerful new processor. The ESP32 has both WiFi and Bluetooth Classic/LE support. That means it's perfect for just about any wireless or Internet-connected project.


The ESP32 is a perfect upgrade from the ESP8266 that has been so popular. In comparison, the ESP32 has way more GPIO, plenty of analog inputs, two analog outputs, multiple extra peripherals (like a spare UART), two cores so you don't have to yield to the WiFi manager, much higher-speed processor, etc. etc!


Comes fully assembled and tested, pre-programmed with ESP32 SPI WiFi co-processor firmware that you can use in MicroPython / CircuitPython / Arduino IDE. 


The end of the breakout have an "FTDI" pinout so you can plug in an [FTDI Friend](https://www.adafruit.com/product/284) or [console cable](https://www.adafruit.com/product/70) to upload MicroPython, Upload software and read/write script and see debugging information via the UART. Then, before uploading code, put it into bootloader mode by holding down the GPIO #0 button and clicking Reset button, then releasing the #0 button.


When you're done with your coding, remove the cable, and this little module can be embeded into your project box.

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
* [Adafruit HUZZAH32 – ESP32 Breakout Board](https://www.adafruit.com/product/4172)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

