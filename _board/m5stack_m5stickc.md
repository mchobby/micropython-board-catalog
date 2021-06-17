
---
layout: download
board_id: "m5stack_m5stickc"
title: "M5StickC ESP32-PICO Mini IoT Download"
name: "M5StickC ESP32-PICO Mini IoT Development Kit (ESP32-PICO) Board"
manufacturer: "M5Stack"
board_url: "https://shop.m5stack.com/products/stick-c"
board_image: "m5stack_m5stickc.jpg"
date_added: 2021-6-11
downloads_display: true
download_instructions: "http://micropython.org/download/tinypico/"
mcu: "ESP32-PICO-D4"
gpio: "3"
ram: "520"
flash: "0"
ext_ram: "0"
ext_flash: "4096"

mcu_category: "ESP32"

machine_api:
  - Pin
  - ADC ?
  - PWM ?
  - UART ?
  - I2C ?
  - SPI ?
  - RTC ?
  - Timer ?
  - WDT ?

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Display 80*160 (ST7735S)
  - 2 User buttons
  - Red LED
  - Micro (SPM1423)
  - RTC (BM8563)
  - IR (Infrared Transmission)
  - Grove connector
  - Lipo 95 mAh
  - 6-Axis IMU
  - USB Type C
---

**M5StickC is a mini M5Stack**, powered by ESP32. It is a portable, easy-to-use, open source, IoT development board. What it can do? This tiny block is able to realize your idea, enlighten your creativity, and help with your IoT prototying in a very short time. It will take away a lot of pains from the development process.M5stickC is one of the core devices in M5Stack product series.

It is built in a continually growing hardware and software ecosystem. It has a lot of compatible modules and units, as well as the open source code & engineering communities that will help you maximize your benefits in every step of the developing process.


Baud rate supported by M5StickC: 1200 ~115200, 250K, 500K, 750K, 1500K


Accordingly to the M5Stack support, you can run the official [MicroPython for TinyPico](http://micropython.org/download/tinypico/) **but will lake of driver**. The st7735 display driver can easily be found with an Internet Search on "micropython ST7735S".


**Features:**
* ESP32-PICO-D4 based @ 240 MHz
* Buttons,Color LCD, Power/Reset button
* Magnetic suction at back
* Extendable ports (3 pins + Grove)
* Wearable
* Program Platform: UIFlow, MicroPython, Arduino


## Purchase
* [M5StickC ESP32-PICO Mini IoT Development Kit](https://shop.m5stack.com/products/stick-c)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).
