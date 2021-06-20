
---
layout: download
board_id: "nucleo_f401re"
title: "STM32 Nucleo-64 Download"
name: "STM32 Nucleo-64 development board"
manufacturer: "STMicroelectronics"
board_url: "https://www.st.com/en/evaluation-tools/nucleo-f401re.html"
board_image: "nucleo_f401re.jpg"
date_added: 2021-6-20
downloads_display: true
download_instructions: "http://micropython.org/download/stm32/"
mcu: "STM32F401RET6U"
gpio: "81"
ram: "96"
flash: "512"
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
  - WDT ?
  - SDCard ?

features:
  - Arduino PinOut
  - STM32F401RET6U @ 84 MHz, Cortex M4 (DSP, FPU, LQFP64 package)
  - 1 user LED shared with ARDUINO
  - 1 user and 1 reset push-buttons
  - 32.768 kHz crystal oscillator
  - Board connectors:ARDUINO Uno n connector. ST morpho extension pin headers for full access to all STM32 I/Os.
  - Flexible power-supply options: ST-LINK, USB VBUS, or external sources
  - On-board ST-LINK debugger/programmer with USB re-enumeration capability: mass storage, Virtual COM port and debug port
  - Comprehensive free software libraries and examples (with the STM32Cube MCU Package)
  - Support of a wide choice IDEs (IAR Embedded Workbench®, MDK-ARM, STM32CubeIDE)

---

The STM32 Nucleo-64 board provides an affordable and flexible way for users to try out new concepts and build prototypes by choosing from the various combinations of performance and power consumption features, provided by the STM32 microcontroller. For the compatible boards, the external SMPS significantly reduces power consumption in Run mode.


The ARDUINO® Uno V3 connectivity support and the ST morpho headers allow the easy expansion of the functionality of the STM32 Nucleo open development platform with a wide choice of specialized shields.


The STM32 Nucleo-64 board does not require any separate probe as it integrates the ST-LINK debugger/programmer.


The STM32 Nucleo-64 board comes with the STM32 comprehensive free software libraries and examples available with the STM32Cube MCU Package. 


**Features:**
* 5V tolerant IO
* Arduino Compatible PinOut
* All MCU pins break out
* Single core Cortex M4 @ 84MHz
* 96kB on-chip SRAM
* 512KB of Flash
* 81 GPIO pins (16x 12 bits ADC inputs)
* User button
* RTC 32.768 KHz oscillator
* Peripherals
  * 3x UARTs (USART)
  * 3x I2C
  * 4x SPI
  * 11x Timer channels
  * SDIO
  * I2S (multiplex with SPI)
* USB 2.0
* On-board ST-LINK debugger/programmer:
  * USB re-enumeration capability,
  * mass storage, 
  * Virtual COM port,
  * Debug port

## Purchase
Add any manufacturer links to purchase the board
* [STMicroelectronics](https://www.st.com/en/evaluation-tools/nucleo-f401re.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

