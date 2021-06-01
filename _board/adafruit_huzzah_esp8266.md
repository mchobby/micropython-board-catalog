
---
layout: download
board_id: "adafruit_huzzah_esp8266"
title: "Adafruit HUZZAH ESP8266 Breakout Download"
name: "Adafruit HUZZAH ESP8266 Breakout"
manufacturer: "Adafruit Industries"
board_url: "https://www.adafruit.com/product/2471"
board_image: "adafruit_huzzah_esp8266.jpg"
date_added: 2020-5-17
downloads_display: true
download_instructions: "http://micropython.org/download/esp8266/"
mcu: "ESP8266 SP-12"
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
  - Wi-Fi
  - Bluetooth/BTLE
---

Add Internet to your next project with an adorable, bite-sized WiFi microcontroller, at a price you like! The ESP8266 processor from Espressif is an 80 MHz microcontroller with a full WiFi front-end (both as client and access point) and TCP/IP stack with DNS support as well. While this chip has been very popular, its also been very difficult to use. Most of the low cost modules are not breadboard friendly, don't have an onboard 500mA 3.3V regulator or level shifting, and aren't CE or FCC emitter certified....UNTIL NOW!


The Adafruit HUZZAH ESP8266 breakout is what Adafruit's designed to make working with this chip super easy and a lot of fun. Adafruit took a certified module with an onboard antenna, and plenty of pins, and soldered it onto our designed breakout PCBs.


The end of the breakout have an "FTDI" pinout so you can plug in an [FTDI Friend](https://www.adafruit.com/product/284) or [console cable](https://www.adafruit.com/product/70) to upload MicroPython, Upload software and read/write script and see debugging information via the UART. Once the "FTDI" adapter plugged on the "FTDI port" the board will run as a Feather ESP8266.


When you're done with your coding, remove the cable, and this little module can be embeded into your project box.

**Features:**
* Reset button,
* User button that can also put the chip into bootloading mode,
* Red LED you can blink,
* Level shifting on the UART and reset pin,
* 3.3V out, 500mA regulator (you'll want to assume the ESP8266 can draw up to 250mA so budget accordingly)
* Two diode-protected power inputs (one for a USB cable, another for a battery)
* 1 x Analog input (1.0V max)
* 9 x GPIO (3.3V logic), which can also be used for I2C or SPI
* 2 x UART pins
* 2 x 3-6V power inputs, reset, enable, LDO-disable, 3.3V output

## Purchase
* [Adafruit HUZZAH ESP8266 Breakout](https://www.adafruit.com/product/2471)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

