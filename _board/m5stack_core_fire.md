
---
layout: download
board_id: "m5stack_core_fire"
title: "M5Stack FIRE IoT Development Kit Download"
name: "M5Stack FIRE IoT Development Kit (ESP32, PSRAM 2.0) Board"
manufacturer: "M5Stack"
board_url: "https://shop.m5stack.com/products/fire-iot-development-kit"
board_image: "m5stack_core_fire.jpg"
date_added: 2021-6-11
downloads_display: true
download_instructions: "https://github.com/m5stack/M5Stack_MicroPython"
mcu: "ESP32-D0WDQ6"
gpio: "14"
ram: "520"
flash: "0"
ext_ram: "4096"
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
  - WDT

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - Display 320*200 IPS (ILI9342C)
  - User buttons
  - Grove connector
  - Lipo 500 mAh
  - SDCard
  - 4 Mio of external PSRam
  - USB Type C
  - 6-Axis posture acceleration measurement (MPU6886)
  - 3-Axis magnetic measurement (BMM150)
---

__M5Stack FIRE Kit__, as one of the M5Stack developing kit series, is an upgrade from the Gray kits. Providing 9-Axis IMU sensor(6-Axis posture acceleration measurement + 3-Axis magnetic measurement), it equips with more hardware resources : 16M Flash + 4M PSRAM , enhanced Base (M5GO Base and M5GO CHG Base), larger battery, etc. For those developers who ask for hardware performance, Fire will be a good choice.

With a IMU posture sensor, there are a lot of situations which you can apply this kit to: detecting acceleration, angulation, and trajectory. You can make relative products like sports data collector, 3D remote gesture controller and more base on the above functions.

FIRE is M5 Core device. Its modular, stackable, scalable, and portable device is powered with an ESP-32 core, which makes it open source, low cost, full-function, and easy for developers to handle new product development on all stages include circuit design, PCB design, software, mold design and production.

M5Stack Fire comes with three separable parts. The top part ,just like Basic and Gray Kit, has all kinds of processors, chips ,sockets, 2.4G antenna, ESP32, power management IC , a LCD screen and some other interface components. The middle part is called M5GO base which provides a lithium battery, M-BUS socket , LED bar and three more GROVE Ports. The bottom part is a charge table, which can be connected to the M5GO base via POGO pins.

If you want to explore the fastest way of IoT prototyping, M5Stack development board is the perfect solution. Not like others, M5Stack development board is highly efficient, covered with industrial grade case and __ESP32-based__ development board. It integrates with Wi-Fi & Bluetooth modules and contains a dual-core and 16MB of SPI Flash . Together with 30+ M5Stack stackable modules , 40+ extendable units and different levels of program language, you can create and verify your IoT product in a very short time.

Supportive development platforms and programming languages: Arduino, Blockly language with UIFlow, Micropython. Regardless of what level programming skill you have, M5Stack would guide you in every step of the way to realize your idea as well as to the final productlization.

__PSRAM Notice:__

The GPIO 16 / 17 in Fire is connected to the PSRAM by default, so when you connect or stack other function modules, you need to avoid conflicts with these two pins to prevent the device from working improperly and causing instability.

See the __[M5Stack Micropython Base](https://github.com/m5stack/M5Stack_MicroPython) GitHub repository__.


See the __[French MicroPython on M5Stack installation guide](https://blog.flozz.fr/2019/07/15/micropython-sur-le-m5stack/)__ by Flozz.


**Features:**
* ESP32-based
* Built-in Speaker, Buttons,Color LCD, Power/Reset button
* TF card slot (16G Maximum size)
* Magnetic suction at back
* Extendable Pins & Holes
* M-Bus Socket & Pins
* Program Platform: UIFlow, MicroPython, Arduino
* 2x LEGO block
* 5x LEGO connector
* M5GO Charging Base


## Purchase
* [M5Stack FIRE IoT Development Kit (ESP32, PSRAM 2.0)](https://shop.m5stack.com/products/fire-iot-development-kit)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).
