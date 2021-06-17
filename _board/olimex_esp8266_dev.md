
---
layout: download
board_id: "olimex_esp8266_dev"
title: "MOD-WIFI-ESP8266-DEV Download"
name: "MOD-WIFI-ESP8266-DEV : ESP8266EX WiFi Development plateform"
manufacturer: "Olimex"
board_url: "https://www.olimex.com/Products/IoT/ESP8266/MOD-WIFI-ESP8266-DEV/open-source-hardware"
board_image: "olimex_esp8266_dev.jpg"
date_added: 2021-5-19
downloads_display: true
download_instructions: "https://wiki.mchobby.be/index.php?title=FEATHER-CHARGER-MICROPYTHON-ESP8266-EN"
mcu: "ESP8266EX"
gpio: "9"
ram: "80"
flash: "0"
ext_ram: "0"
ext_flash: "2048"

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
  - Wi-Fi
  - Bluetooth/BTLE
---

MOD-WIFI-ESP8266-DEV is development board with the famous ESP8266EX WIFI IC. Our module comes with 2MB (16Mb) of SPI flash memory, and all GPIO resources are available for breadboarding. The I2C and SPI interfaces are also available. It is easy to implement the module in your existing designs - you might even solder it diretly on other PCBs as it has no components on the bottom side. The module be used for home automation, smart plugs and lights, mesh networks, industrial wireless control, baby monitors, IP cameras, sensor networks, wearable electronics, etc.

This product requires Console debug cable to get programmed.

**Features:**

* Main chip: EPS8266EX
* 2Mio SPI flash memory
* Power LED
* User-programmable LED
* Button for UART/FLASH mode (since hardware revision B)
* SMT jumpers for different boot modes (FLASH, UART, SDO)
* PCB antenna
* UEXT pads for easier access to UART interface
* Pads for a µFL antenna connector (if you want to use external antenna)
* 22 pin holes @ 0.1" step for easier access to processor pins
* OSHW desgn
* Dimensions: 3.3 x 2.3 cm


## Purchase
* [MOD-WIFI-ESP8266-DEV board](https://www.olimex.com/Products/IoT/ESP8266/MOD-WIFI-ESP8266-DEV/open-source-hardware)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

