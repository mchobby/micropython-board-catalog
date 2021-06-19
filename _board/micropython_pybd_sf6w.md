---
layout: download
board_id: "micropython_pybd_sf6w"
title: "Pyboard D-Series SF6W STM32F767 Download"
name: "Pyboard D-Series SF6W STM32F767"
manufacturer: "George Robotics Limited"
board_url: "https://store.micropython.org/product/PYBD-SF6-W4F2"
board_image: "micropython_pybd_sf6w.jpg"
date_added: 2021-6-19
downloads_display: true
download_instructions: "https://micropython.org/download/pybd/"
mcu: "STM32F767VIT"
gpio: "46"
ram: "512"
flash: "2048"
ext_ram: "0"
ext_flash: "2048"

mcu_category: "STM32"

machine_api:
  - Pin 
  - ADC
  - UART
  - I2C
  - SPI
  - RTC
  - Timer
  - WDT

features:
  - Wi-Fi
  - Bluetooth/BTLE
  - USB Host
  - SDCard
---

The concept for the D-series of pyboards is a miniature DIP-style form factor useful as both a standalone board and an embedded component for use in final products. On the underside is our WBUS header, a 40+40-pin mezzanine bus connector giving access to all power and IO ports in a highly compact form factor. The WBUS can be used to bring out the IO lines for easy access and prototyping, as well as providing a way to integrate the board into a larger system.


The pyboard also provides native USB connectivity to provide direct and convenient access to the software running on the board. It can connect to your PC over USB, giving you a USB flash drive to save Python scripts and data files, and a serial Python prompt (a REPL) for instant programming.


The pyboard runs MicroPython, which is a complete re-write of the Python (version 3.4) programming language so that it fits and runs on a microcontroller. It includes many optimisations so that it runs efficiently and uses very little RAM.


MicroPython runs bare-metal on the pyboard, and essentially gives you a Python operating system. The built-in pyb and machine modules contain functions and classes to control the peripherals available on the board, such as UART, I2C, SPI, ADC and DAC. Watch this video for an overview of the original pyboard.


There are 4 main ways to control the pyboard:
* **REPL**: Connecting to your PC via USB, the board appears as a USB virtual comms port (CDC VCP) and you can use any serial program to connect and get a Python REPL prompt. This allows you to instantly type and execute Python commands, just like you would when running Python on your PC. You can also redirect the REPL to any of the UARTs on the pyboard.
* **Remote script**: You can change from REPL to raw REPL mode by sending ctrl-A, and then in raw REPL mode you can send an arbitrary Python script to the board for it to execute immediately. A Python script is available which makes using this mode very simple: you just run python pyboard.py script_to_run.py and this will execute script_to_run.py on the pyboard, returning any output.
* **From file**: The pyboard has a small, built-in filesystem which lives in external flash memory. It also has an SD card slot if you want to extend the available storage. When you connect the pyboard to your PC, it appears as a USB flash storage device and you can access (mount) the internal filesystem and the SD card this way. If you copy a Python script to the filesystem and call it main.py then the board will execute this script when it starts up. This way you can run scripts without being connected to a PC. Scripts can also be pre-compiled to Python bytecode (so-called .mpy files) to enable faster loading at runtime.
* **Via frozen code**: Once an application has been developed it can be pre-compiled and frozen into the main firmware. This gives minimal overhead for RAM usage and start-up time. This is an advanced feature and requires you to recompile the C-based firmware.


**Features:**
* STM32F767VIT microcontroller
* 216 MHz Cortex M7 CPU with single-precision hardware floating point
* 2048KiB internal flash ROM and 512KiB internal RAM
* 2MiB external QSPI flash with execute capabilities to extend internal flash
* Additional 2MiB external QSPI flash for user filesystem and storage
* Integrated, high-performance WiFi and Bluetooth 4.1 (classic and BLE) via Murata 1DX module (with CYW4343)
* TCP/IP and Bluetooth stacks run on the main microcontroller, fully customisable
* On-board fractal chip antenna for WiFi and Bluetooth
* uFL connector for attaching external antenna, selectable via RF switch
* Micro USB connector for power and serial communication
* Micro SD card slot, supporting standard and high capacity SD cards
* Real time clock with highly accurate pre-calibrated external oscillator
* Physical electrical connectivity via 24 through holes, and a 40+40 pin mezzanine bus connector
* 46 independent GPIO, with 24 available via through holes
* Additional 11 GPIO shared with SD card, USB, USR button, BT audio
* 2x I2Cs, 
* 4x UARTs, 
* 3x SPIs, 
* 1x CAN interfaces
* 3x 12-bit analog to digital converters (ADC), available on 16 independent pins
* 2x 12-bit digital to analog converters (DAC), available on 2 independent pins
* 1x 3-colour RGB LED
* 1 reset and 1 user button
* On-board 3.3V LDO voltage regulator to supply main microcontroller
* Additional, user switchable, on-board 3.3V LDO voltage regulator to power SD card and external components
* 2 mounting points
* Custom DFU bootloader for easy upgrading of firmware


## Purchase
* [store.MicroPython.org](https://store.micropython.org/product/PYBD-SF6-W4F2)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

