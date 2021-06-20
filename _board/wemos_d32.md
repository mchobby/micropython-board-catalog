
---
layout: download
board_id: "wemos_d32"
title: "Wemos/LOLIN D32 Download"
name: "Wemos/LOLIN D32 (ESP32)"
manufacturer: "Wemos"
board_url: "https://www.wemos.cc/en/latest/d32/d32.html"
board_image: "olimex_esp32_evb.jpg"
date_added: 2021-5-20
downloads_display: true
download_instructions: "http://micropython.org/download/esp32/"
mcu: "ESP32-WROOM-32"
gpio: "22"
ram: "512"
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
  - RTC ?
  - Timer
  - WDT
  - SDCard ?

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Battery Charging
  - USB to Serial
---

The LOLIN D32 IoT development platform if propelled with ESP32 and 4MB of Flash

The Wemos LOLIN D32 is the Wemos platform succeeding the D1 Mini based on ESP8266.

With the D32, you have an ESP32-WROOM-32 with 4MB of Flash memory, 512 KB of RAM, ideal for projects using Arduino IDE or MicroPython. The D322 is also delivered with MicroPython preloaded on the board.

The **Lipo charger** also has a JST PH connector for the connection of a Lipo Battery (see  our range of batteries). Recharging the battery is supported by a TP4054, an LED indicates when the battery is charging (when the board is connected via USB).
Finally, it is possible to have an indication of the charge on the IO35 since the battery is connected to it via a voltage divider bridge 100 KOhms - 100 KOhms. The battery voltage is therefore halved.

Flash the **generic** ESP32 MicroPython firmware.


**Features:**
* ESP32-WROOM-32 @ 240 MHz
* 4 MBytes Flash
* 22 digital Input/Output
* 6 analog input (3.3V)
* 2 analog output (DAC, 3.3V)
* LED on IO5 (reverse logic)
* USB-serial converter (CH340C).
* Lipo battery charger

## Purchase
* [Wemos.cc](https://www.wemos.cc/en/latest/d32/d32.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

