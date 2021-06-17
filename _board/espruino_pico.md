
---
layout: download
board_id: "espruino_pico"
title: "Espruino Pico Download"
name: "Espruino Pico"
manufacturer: "Espruino"
board_url: "https://www.espruino.com/Pico"
board_image: "espruino_pico.jpg"
date_added: 2021-6-17
downloads_display: true
download_instructions: "http://micropython.org/download/espruino_pico/"
mcu: "STM32F401CDU6"
gpio: "22"
ram: "96"
flash: "384"
ext_ram: "0"
ext_flash: "0"

mcu_category: "STM32"

machine_api:
  - Pin
  - ADC ?
  - PWM ?
  - UART
  - I2C
  - SPI
  - RTC ?
  - Timer
  - WDT
  - SDCard ?

features:
  - USB Host
  - Tolerant 5V
---

Introducing the Espruino Pico to control electronics with a tiny USB stick that runs JavaScript or MicroPython. The Espruino Pico is tiny small built on a STM32 microcontroller pre-programmed with Espruino (JavaScript for Microcontroler).


The Espruino Pico is a kind of USB with GPIOs with built-in JavaScript interpreter or MicroPython virtual machine. It allows you to run run scripts on the this small microcontoler. Simply set up your Javascript or MicroPython code with the Espruino and send it to the device without having to wait for the board to 'flash.'


The Pico is designed to include it into your own designs and builds. The 2.54mm pins are easy to fit into breadboard (or socket) where as the castellates allows you to use the the Pico as a SMD component.


The Espruino Pico can also be used with operating system supporting USB-to-Serial (Windows, Mac, Linux, Android, Raspberry, etc). The Pico can also be controled from the host via this USB-to-Serial port.


Don't be fooled by its size, the Pico have lots of I/O. Thanks to the USB interface (and USB-to-Serial) the Pico can also be used ad IO board for PCs, Macs and Linux machine.


[Espruino Pico page](https://www.espruino.com/Pico) including [tutorials](https://www.espruino.com/Pico#tutorials), [PinOut](https://www.espruino.com/Pico#pinout), [datasheets](https://www.espruino.com/datasheets/STM32F401xD.pdf), and more!


**Features:**
* Single core 32-bit ARM Cortex M4 CPU @ 84 MHz
* 96kB on-chip SRAM
* 384 KB Flash
* 22 GPIO pins (9 ADC inputs)
* Onboard USB A connector
* Peripherals
  * 2x UARTs
  * 3x I2C controllers
  * 21x PWM channels
  * 5 volts tolerants.


## Purchase
* [Espruino, Pico](https://www.espruino.com/Pico)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

