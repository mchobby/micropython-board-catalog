---
layout: download
board_id: "micropython_pyboard"
title: "Pyboard V1.1 Original Download"
name: "Pyboard V1.1 Original"
manufacturer: "George Robotics Limited"
board_url: "https://store.micropython.org/product/PYBv1.1H"
board_image: "micropython_pyboard.jpg"
date_added: 2021-5-08
downloads_display: true
download_instructions: "https://micropython.org/download/pybv1/"
mcu: "STM32F405RG"
gpio: "30"
ram: "192"
flash: "1024"
ext_ram: "0"
ext_flash: "0"

mcu_category: "STM32"

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
  - Robotics
  - USB Host
  - SDCard
---

PyBoard, the MicroPython board is a small electronic board that runs Micro Python in "Bare Metal" and offers a low-level Python operating system to control all kinds of electronic projects. 


Python is a very easy to learn scripting language, very expressive, very powerful and has a huge community. By operating on a micro controller, Micro Python makes it possible to flash LEDs without any effort, read voltages, move motors and servo motors, play sound, write/read data on the micro SD card, establish wireless communications (with an additional module) and become that brain that your robot is desperately waiting for. There are so many other opportunities accessible to PyBoard and Micro Python

The MicroPython PyBoard is an electronic development board based on STM32F405 micro controller that runs Micro Python. This micro controller is one of the most powerful micro controllers available on the market and has been specially selected because it would allow micropython to operate at its full potential. 

The board includes a USB interface that is presented as a serial device (CDC VCP) and as a removable USB storage device (MSC, the equivalent of your USB key). When PyBoard is connected to a computer, you can open a serial communication program (telnet/minicom or Putty terminal) and interact the board via a Python command line.
The board also behaves like a storage device (a USB Flash drive) allowing you to easily copy your scripts to the file system of the board or SD card. These files can be executed independently of the computer.

Pyboard Hardware features:
* **30 GPIO** - Input / output pins that can be used for many applications. With a GPIO, you can control LEDs, relays (via transistor or UNL2803), motors (via L293). Read the state of buttons and sensors. Control devices such as LCD screens, graphic displays, expansion cards, etc.
* **2 I2C buses** - To control devices using 3 wires.
* **2 CAN buses**
* **2 SPI buses**
* **5 UARTs** - A serial port is a very useful communication tool ... having 5 is absolutely great.
* **20 PWMs** - Provides signals to control servo motors or the power of a LED
* **16 ADC** - Analog-to-Digital converter for analog voltage reading (convenient for use with flex sensors, photo resistance, potentiometer, etc.)
* **2 DAC** - Very rare on the prototyping boards, Digital-to-Analog converters can produce analog output voltages. With this you can produce various types of signals (sawtooth, sinusoid, ... and even sound).
* **13 timers** - Timers measure duration and execute code / function at regular intervals. This is an important synchronization element when you want to write advanced applications.
* **16 ext int** - External interrupts allows to interrupt the main program to execute code (interrupt function) when a pin changes state. This makes it possible to write programs that react instantly to the change in physical conditions around the board. Example: stop motors immediately if the emergency stop is activated.
* **1 RTC** - The real-time clock lets you know the time, measure time laps large enough, create calendar-based executions, and make clocks. The RTC is a useful element that is often missing in prototyping platforms (as is the case for Raspberry, Arduino or Spark Core where the RTC is not used)
* **4 LEDs** - LEDs / DELs are useful for informing the user about the status of the program. Having them on the board allows you to quickly test / prototype code without having to make connections.
* **1 Accelerometer** - Such a device makes it possible to measure the acceleration (practical case: a falling smartphone) but especially the terrestrial G acceleration on the 3 axes. This earth acceleration responsible for gravity is directed towards the center of the earth, by measuring this acceleration on 3 axes, it is thus possible to determine the 3D position / orientation of the board with respect to the ground (practical case: the automatic rotation of screens on a smartphone, balancing act for a biped robot).

**Features:**
* Microcontroller STM32F405RG (data sheet)
* CPU Cortex-M4 cadenced 168 MHz with 32-bit floating computing unit.
* 1 Mb of Flash memory for storage, 192 Kb of RAM.
* MicroB USB connector with USB serial software support, USB mass storage device, and USB HID (mouse, keyboard).
* connector for micro SD card.
* FreeScale MMA7660 3-Axis Accelerometer (Data Sheet). Up to 64 6-bit samples per second per axis.
* 4 LEDs, 1 Reset button, a user button.
* A 3.3V LDO regulator (low loss) of 300mA. Powered from the USB connector or external power supply between 3.6V and 10V.
* Real Time Clock (RTC) with date and time.
* 30 GPIO input / output pin, 28 are 5V tolerant (except in ADC / Analog-to-Digital mode).
* RTC : real time clock
* Communication:
 * 2 SPI buses,
 * 2 CAN buses,
 * 2 I2C buses,
 * 5 USART (serial port).
* 14x Analog input with 12-bit resolution, Value between 0 and 4095 (ADC, Analog-to-Digital Converter).
* 2x analog output (DAC, Digital-to-Analog Converter).
* Size: 33 x 40mm.
* Weight: 6 gr.
* 46 holes 2.54mm spacing.

## Purchase
* [store.MicroPython.org](https://store.micropython.org/product/PYBv1.1H)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

