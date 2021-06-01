
---
layout: download
board_id: "olimex_esp32_evb"
title: "ESP32-EVB development board Download"
name: "ESP32-EVB : development board with WiFi BLE Ethernet micro SD card UEXT and GPIO"
manufacturer: "Olimex"
board_url: "https://www.olimex.com/Products/IoT/ESP32/ESP32-EVB/open-source-hardware"
board_image: "olimex_esp32_evb.jpg"
date_added: 2020-5-20
downloads_display: true
download_instructions: "http://micropython.org/download/esp32/"
mcu: "ESP32-WROOM-32"
gpio: "32"
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
  - RTC
  - Timer
  - WDT
  - SDCard

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Battery Charging
  - USB Host
  - SDCard
  - UEXT port
  - Ethernet Link
  - RAW IR Emitter/Receiver
  - CAN transceiver
---

This is the ultimate IoT board with wired 100Mb Ethernet Interface, Bluetooth LE, WiFi, Remote control IR, and CAN connectivity.


Two relays allows you to switch power appliances on and off.


The board can operate with single LiPo backup battery like UPS as it has an internal LiPo battery charger. This will be handy to keeps the MCU powered while power-outtage. 


Notes: 
* There is no step-up converter on the board. 5V power supply cannot be generated from the Lipo in case of Power-Outtage (so relays, CAN and USB power would not work over battery). 
* Controling the full features of this board (Ethernet, IR, CAN) from MicroPython requires advanced development skills.
* Common features like GPIOs, Relay, LED, User Button, UEXT can easily be performed from MicroPython.


**To flash MicroPython on the board** : press the User button, next press & release reset button, finally release the user button.

Flash the **generic** ESP32 MicroPython firmware.


**Features:**
* ESP32-WROOM32 module
* High reliable Industrial grade -40+85C available (-IND)
* Built-in programmer for Arduino and ESP-IDF
* WiFi, BLE connectivity
* Ethernet 100Mb interface
* MicroSD card
* 2 x relays 10A/250VAC with connectors and status LEDs
* CAN interface
* IR received and transmitter (up to 5m)
* LiPo charger with  4 status LEDs
* 5V power jack (alternative to USB power sypply)
* UEXT connector 
* 40 pins GPIO connector (with 32 GPIOs, some shared with the other functions)

## Purchase
* [ESP32-EVB development board](https://www.olimex.com/Products/IoT/ESP32/ESP32-EVB/open-source-hardware)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

