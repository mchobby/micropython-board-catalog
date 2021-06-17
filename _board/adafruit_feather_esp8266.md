
---
layout: download
board_id: "adafruit_feather_esp8266"
title: "Adafruit Feather HUZZAH ESP8266 Download"
name: "Adafruit Feather HUZZAH ESP8266"
manufacturer: "Adafruit Industries"
board_url: "https://www.adafruit.com/product/2821"
board_image: "adafruit_feather_esp8266.jpg"
date_added: 2021-5-17
downloads_display: true
download_instructions: "http://micropython.org/download/esp8266/"
mcu: "ESP8266 ESP-F"
gpio: "9"
ram: "80"
flash: "0"
ext_ram: "0"
ext_flash: "4096"

mcu_category: "ESP8266"

machine_api:
  - Pin
  - ADC
  - PWM
  - UART
  - I2C
  - SPI
  - RTC
  - WDT

features:
  - Feather-Compatible
  - Wi-Fi
  - Bluetooth/BTLE
  - Battery Charging
---

The Adafruit Feather HUZZAH ESP8266 is a on an 'all-in-one' ESP8266 WiFi development board with built in USB and battery charging. Its an ESP8266 WiFi module with all the extras you need, ready to rock! This board is part of the [Feather EcoSystem](https://www.adafruit.com/category/777).

At the Feather HUZZAH's heart is an ESP8266 WiFi microcontroller clocked at 80 MHz and at 3.3V logic. This microcontroller contains a Tensilica chip core as well as a full WiFi stack. You can program the microcontroller using the Arduino IDE for an easy-to-run Internet of Things core. The CP2104 USB-Serial chip from SiLabs can be used that can upload code / script to the ESP8266. The board also feature an auto-reset feature so no noodling with pins and reset button pressings. The CP2104 has better driver support than the CH340 and can do very high speeds without stability issues.

To make it easy to use for portable projects, the board is fitted with Lipo connector for any of our 3.7V Lithium polymer batteries and built in battery charging. You don't need a battery, it will run just fine straight from the micro USB connector. But, if you do have a battery, you can take it on the go, then plug in the USB to recharge. The Feather will automatically switch over to USB power when its available.


**Features:**
* Measures : 51mm x 23mm x 8mm  (without headers soldered in)
* Weight : 9.7 grams
* ESP8266 @ 80MHz with 3.3V logic/power
* 4MB of FLASH (32 MBit)
* Built in WiFi 802.11 b/g/n
* 3.3V regulator with 500mA peak current output
* CP2104 USB-Serial converter onboard with 921600 max baudrate for speedy uploading
* Auto-reset support for getting into bootload mode before firmware upload
* 9x GPIO pins - can also be used as I2C and SPI
* 1x analog inputs 1.0V max
* Built in 100mA LiPoly charger with charging status indicator LED, can also cut a trace to disable the charger
* Pin #0 red LED for general purpose blinking. Pin #2 blue LED for bootloading debug & general purpose blinking
* Power/enable pin
* 4 mounting holes
* Reset button

## Purchase
* [Adafruit Feather HUZZAH with ESP8266](https://www.adafruit.com/product/2821)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

