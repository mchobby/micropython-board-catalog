
---
layout: download
board_id: "sipeed_maixduino"
title: "Maixduino AI Development Download"
name: "Maixduino AI Development - Kit K210 RISC-V AI + IoT ESP32"
manufacturer: "Sipeed"
board_url: "https://www.dfrobot.com/product-1965.html"
board_image: "sipeed_maixduino.jpg"
date_added: 2021-6-17
downloads_display: true
download_instructions: "https://icircuit.net/setting-up-maixduino-with-maixpy/3004"
mcu: "Sipeed M1 (based on K210)"
gpio: "21"
ram: "8192"
flash: "16384"
ext_ram: "0"
ext_flash: "0"

mcu_category: "RISC-V"

machine_api:
  - Pin (**see Maix.GPIO**)
  - ADC (**via ESP32**)
  - PWM
  - UART
  - I2C
  - SPI
  - Timer

features:
  - Neural network processor
  - Arduino Layout
  - Display (touch)
  - Wi-Fi (via ESP32)
  - Bluetooth/BTLE (via ESP32)
  - Speaker output 
  - Mems MicroPhone
  - Audio DAC
  - Camera
  - USB Serial
  - SDCard
---

Maixduino AI development board is based on K210 RISC-V AI processor. The Kendryte K210 is enclosed within the Sipeed M1 AI module (also named Lichee Dan) joined to an ESP32 module visible on the board. The ESP32 is used for WiFi, Bluetooth connectivity and Analog reading. 


K210 is dual-core processor chip with independent Floating Point Unit (FPU), 64 bits CPU bit width, 8 MB on-chip SRAM, 400 adjustable nominal frequency, and double-precision FPU supporting multiplication, division, and square root operation. 


Besides, Maixduino AI Development Board is equipped with neural network hardware accelerator KPU, voice processing unit (APU), programmable IO array (FPIOA/IOMUX), and Fast Fourier Transform Accelerator. In the AI processing, K210 can perform operations such as convolution, batch normalization, activation, and pooling. At the same time, the pre-processing of voice direction scanning and voice data output can also be performed.


The ESP32-WROOM-32 on-board wireless module offers 2.4GHz 802.11.b/g/n WiFi 4 and Bluetooth 4.2 LE connectivity. 


The board is also fitted with DVP camera connector, LCD display connector, built-in MEMS microphone, TM8211 I2S audio DAC, 3W power amplifier, USB 2.0 Device type C port for powering and programming via **dual USB-Serial channel** with the CH522 chip. One channel is linked to K210 and the other channel to ESP32.


Arduino UNO compatible headers with digital I/O, PWM, I2C, UART, 6x analog inputs, and power signals.


The Kit includes: Maixduino controller, 2.4” LCD screen, GC0328 camera


Note: The shape and pins are compatible with Arduino UNO R3 but the **voltage level is not compatible**, which requires great attention, otherwise the board can be damaged. **Maixduino supports 3.3V and 1.8V levels**, and the pins are divided into several BANKs, each BANK can be set to a voltage of 1.8V or 3.3V by software. The pins **are not 5V tolerant**. Therefore, when using the peripheral device of Arduino, be careful not to short the 5V to the pins or RST pins (1.8V). 


**MaixPy** is to port Micropython to K210 (a 64-bit dual-core RISC-V CPU with hardware FPU, convolution accelerator, FFT, Sha256) is a project that supports the normal operation of the MCU and integrates hardware acceleration. AI machine vision and microphone array, 1TOPS computing power core module is less than ￥50, in order to quickly develop intelligent applications in the field of AIOT with extremely low cost and practical size.


MaixPy is supporting a part of the MicroPython machine API (the Pin class is not implemented, see the Maix.GPIO class).


MaixPy is pre-installed on the board and you can directly start a REPL session on the USB-Serial port attached to the Kendrite (warning, the board expose 2 USB-Serial port, the other one is for the ESP32).


**Ressources:**
* Start REPL session with Putty at 115200 bauds
* [MaixPy English Wiki](https://wiki.sipeed.com/soft/maixpy/en/) from Sipeed
* [MaixPy Example scripts](https://github.com/sipeed/MaixPy_scripts) from Sipeed
* [MaixPy Examples (including ADC read)](https://beta-notes.way-nifty.com/blog/2020/03/post-48b886.html) from beta-notes.way-nifty.com
* [MaiXPy MicroPython Firmware](https://dl.sipeed.com/MAIX/MaixPy/release/master/) and [how to re-install it](https://icircuit.net/setting-up-maixduino-with-maixpy/3004) (from icircuit.net).
* [maixpy.io](http://maixpy.io/)
* [MaixPy Forum](https://en.bbs.sipeed.com/)

**Features:**
Do not forget to insert summary with plateform features like the following (no text, just list).
* Dual core RISC-V 64 bit processor with FPU runs at 400Mhz
* KPU CNN Accelerator (Neural Network Unit)
* APU Audio/Voice Processing Unit
* 8MB on-chip SRAM
* ??? Flash
* 21 GPIO pins (6 ADC inputs via ESP32)
* Peripherals
  * 1x UARTs
  * 1x I2C
  * ?* SPI
  * 13x PWM channels
  * 
* Hardware accelerator
  * FFT (Fast Fourrier Transform),
  * AES,
  * SHA256 
* 2.4" LCD TFT
* Camera GC0328
* Wireless support
  * ESP32-WROOM-32 
  * WiFi 802.11 b/g/n
  * Bluetooth 4.2 / BLE / Classic

## Purchase
Add any manufacturer links to purchase the board
* [Taobao - Sipeed official shop](https://sipeed.world.taobao.com/)
* [MaixDuino, DFRobot](https://www.dfrobot.com/product-1965.html)
* [MaixDuino, SeeedStudio](https://www.seeedstudio.com/Sipeed-Maixduino-Kit-for-RISC-V-AI-IoT-p-4047.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

