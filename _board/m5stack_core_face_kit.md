
---
layout: download
board_id: "m5stack_core_face_kit"
title: "M5Stack Core Face Kit Download"
name: "M5Stack Core Face Kit (ESP32) Board"
manufacturer: "M5Stack"
board_url: "https://docs.m5stack.com/en/core/face_kit"
board_image: "m5stack_core_face_kit.jpg"
date_added: 2021-6-2
downloads_display: true
download_instructions: "https://github.com/m5stack/M5Stack_MicroPython"
mcu: "ESP32-D0WDQ6"
gpio: "14"
ram: "520"
flash: "0"
ext_ram: "0"
ext_flash: "16384"

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

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Display 320*200 IPS (ILI9342C)
  - User buttons
  - 6 axis IMU
  - Grove connector
  - Lipo 600 mAh
  - SDCard
  - USB Type C
---
**FACES Kit** is a series of functional panels integration for the M5Stack Core Gray (included, The GRAY is an update of the Core Basic). The FACES Kit Gray contains three most commonly used panels integration containing three most commonly used panels 'GameBoy'，'Calculator' and 'QWERTY'. With **MEGA328** processor built inside the panels, it works under slave mode through I2C communication protocol. With these 3 different panels, it will be very easy to support keyboard interaction with your M5Core.


See the __[M5Stack Micropython Base](https://github.com/m5stack/M5Stack_MicroPython) GitHub repository__.


See the __[French MicroPython on M5Stack installation guide](https://blog.flozz.fr/2019/07/15/micropython-sur-le-m5stack/)__ by Flozz. 


**Features:**
* ESP32-based
* Built-in Speaker, Buttons,Color LCD, Power/Reset button
* TF card slot (16G Maximum size)
* Extendable Pins & Holes
* M-Bus Socket & Pins pugged on FACEs
* 6 Axis IMU: BMM150 + MPU6886
* Program Platform: UIFlow, MicroPython, Arduino
* **Charger support** for Faces
* **Face Qwerty Keyboard**
* **Face GamePad** (GameBoy alike)
* **Face Caculator**


## Purchase
* [M5Stack Core Face Kit](https://docs.m5stack.com/en/core/face_kit)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).
