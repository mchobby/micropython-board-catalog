
---
layout: download
board_id: "pycom_lopy4"
title: "LoPy4 Download"
name: "LoPy4"
manufacturer: "Pycom"
board_url: "https://pycom.io/product/lopy4/"
board_image: "pycom_lopy4.jpg"
date_added: 2020-6-16
downloads_display: true
download_instructions: "https://pycom.io/product/lopy4/"
mcu: "STM32"
gpio: "24"
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
  - LoRa
---

The LoPy4 is a compact quadruple network MicroPython enabled development board (**LoRa, Sigfox, WiFi, Bluetooth**). It’s the perfect enterprise grade IoT platform for your connected Things. With the latest Espressif ESP32 chipset the LoPy4 offers a perfect combination of power, friendliness and flexibility. Create and connect you things everywhere. Fast.


The LoPy4 can act as a LoRa nano gateway and a multi-bearer (LoRa, Sigfox, WiFi and BLE) development platform suitable for all LoRa and Sigfox networks around the globe. It is programmable with MicroPython and the Pymakr plugins for fast IoT application development, easy programming in-field and extra resilience with network failover. You can also configure the LoPy4 in raw LoRa mode to send packets directly between LoPy4’s. The best blend of speed to deployment and access to new LPWAN networks rolling out across Europe, USA, Africa and India. The LoPy4 is CE, FCC, IC, RCM approved, LoRaWAN and Sigfox certified.


The board ships with or without male headers mounted as seen on the pictures.


NOTE:
* This divice can also be used as Nano LoRa gateway (Up to 22km, capacity up to 100 nodes) 
* Using the LoRa or Sigfox radio without the external antenna can lead to damage of the device and is therefore not recommended.


If you are purchasing the LoPy4 and wish to connect via USB to your computer, you will also need to purchase either the [Expansion Board 2.0](https://pycom.io/product/expansion-board-3-0/), [Pysense](https://pycom.io/product/pysense/) or [Pytrack](https://pycom.io/product/pytrack/).



**Features:**
* ESP32 based plateform
* Network processor handles the WiFi connectivity and the IPv6 stack
* WiFi & BLE
* 512kB on-chip SRAM
* 8MB external Flash
* 4MB External RAM
* 24 GPIO pins (8 ADC inputs @ 12 bits)
* Hardware floating point acceleration
* Python multi-threading
* Peripherals
  * 2x UARTs
  * 1x SPI
  * 2x I2C
  * I2S
  * micro SDCard
  * 4x Timer 16 bits (PWM capable)
* SigFox - Up to 50km
  * RCZ1 – 868MHz (Europe)
  * RCZ2 – 902MHz (US, Canada and Mexico)
  * RCZ3 – (Japan and Korea)
  * RCZ4 – 920-922MHz (ANZ, Latin America and S-E Asia)
* Lora - Up to 40km
  * 868 MHz (Europe) at 14dBm maximum
  * 915 MHz (North and South America, Australia and New Zealand) at 20dBm maximum
  * 433 MHz (Europe) at 10dBm maximum
  * 470 – 510 MHz (China) at 14dBm maximum
* Security & Certifications
  * SSL/TLS support
  * WPA Enterprise security
  * FCC 2AJMTLOPY4R
  * CE 0700


## Purchase
* [Pycom - LoPy4](https://pycom.io/product/lopy4/)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

