
---
layout: download
board_id: "wemos_d1_mini"
title: "Wemos/LOLIN D1 Mini Download"
name: "Wemos D1 Mini"
manufacturer: "Wemos"
board_url: "https://www.wemos.cc/en/latest/d1/d1_mini.html"
board_image: "wemos_d1_mini.jpg"
date_added: 2021-6-20
downloads_display: true
download_instructions: "https://micropython.org/download/esp8266/"
mcu: "ESP-8266EX"
gpio: "11"
ram: "96"
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
  - Timer
  - WDT
  - SDCard ?

features:
  - Wemos connector
  - Wi-Fi
  - Bluetooth
  - USB Host
---

The Wemos D1 mini is a popular ESP8266 development plateforme that can be programmed with Arduino IDE, NodeMCU (lua script) and MicroPython for ESP8266.


This is the lastest version of D1 Mini (v3.0.0) offering the latests features:
* An optimized circuit
* A deep-sleep jumper
* The MicroPython for ESP8266 as default Firmware.
* But you can easily use it with Arduino IDE or reflash it to support NodeMCU (Lua Script)


The Key advantage of the Wemos Plateform is to offers a lot of shield and add-ons and it also support the famous NeoPixel (smart RGB Led) for create smart display and animation.


The plateforme offers 11 digital I/O and 1 analog input. The Wemos is the only plateform supporting a 3.3V input voltage the analog input (thank to the voltage resistor divider placed on the 1V max analog input of the ESP8266).


As many ESP8266 plateform, this ESP8266 brings 4 Mbytes Flash and a CH340G USB to serial converter (as used by Sparkfun for some of their product). As the USB-to-Serial converter handles the DTR and RTS signal, there is no need for extra button to handle the bootloading activation on GPIO0 :-)


The power supply 5v to 3.3v is handled by the ME6211 regulator offering an output current of 500mA max which leave a room of ~200 to 250mA for your own projet as the ESP8266 use from 40mA-80mA to 250mA while communicating over the WiFi. 


**Features:**
* ESP-8266EXe @ 160/80MHz
* 96kB on-chip SRAM
* 4MB external Flash
* 11 GPIO pins (1 ADC inputs @ 3.3V thanks to voltage divider)
* User LED on D4
* Peripherals
  * 1x UARTs for REPL
  * 1x I2C
  * 1x SPI  
  * PWM on all pins
  * USB-to-Serial converter (CH340G)

## Purchase
Add any manufacturer links to purchase the board
* [Wemos.cc](https://www.wemos.cc/en/latest/d1/d1_mini.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

