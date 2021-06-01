
---
layout: download
board_id: "olimex_esp8266_evb"
title: "MOD-WIFI-ESP8266-EVB Download"
name: "MOD-WIFI-ESP8266-EVB : Development Board"
manufacturer: "Olimex"
board_url: "https://www.olimex.com/Products/IoT/ESP8266/ESP8266-EVB/open-source-hardware"
board_image: "olimex_esp8266_evb.jpg"
date_added: 2020-5-19
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

ESP8266-EVB is board suitable for resarch and development of espressif's ESP8266EX chip. The module be used for home automation, smart plugs and lights, mesh networks, industrial wireless control, baby monitors, IP cameras, sensor networks, wearable wlectronics, etc.
ESP8266EX is very highly integrated SoC which includes Tensilica's L106 32-bit core processor; SRAM; power management unit; RF front end. ESP8266EX has a number of interfaces - I2C, SPI, SDIO and also a number of free GPIO pins. The chip allows the implementation of a WIFI TCP-IP stack with just few extra components beside the ESP8266EX.

This product requires Console debug cable to get programmed.

It also exists a [https://wiki.mchobby.be/index.php?title=ESP8266-DEV French documentation of the usage of this board with MicroPython]. 

**Features:**

* Includes MOD-WIFI-ESP8266-DEV
* Relay 10A/250VAC (15A/120VAC 15A/24VDC) with connector and status LED
* Big button for easier access to UART mode
* Power jack for +5V external power supply
* UEXT connector
* Row of 16 pin holes at 2.54mm step with all ESP8266 signals accessible; male-male 16-pin connector included 
* 4 mounting holes

Microcontroler Feature
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
* [MOD-WIFI-ESP8266-DEV Development board](https://www.olimex.com/Products/IoT/ESP8266/ESP8266-EVB/open-source-hardware)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

