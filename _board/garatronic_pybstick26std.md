---
layout: download
board_id: "garatronic_pybstick26std"
title: "PYBStick 26 Standard Download"
name: "PYBStick 26 Standard"
manufacturer: "Garatronic"
board_url: "https://github.com/mchobby/pyboard-driver/tree/master/PYBStick"
board_image: "shortname.jpg, EG: garatronic_pybstick26std.jpg"
date_added: 2020-5-12
downloads_display: true
download_instructions: "https://github.com/mchobby/pyboard-driver/tree/master/PYBStick/firmware"
mcu: "STM32F411RE"
gpio: "17"
ram: "128"
flash: "512"
ext_ram: "0"
ext_flash: "0"

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
  - USB Host
  - SDCard
---

This product is a PYBStick Standard 26 and is propel by a STM32F411 at 100 MHz, a more powerful microcontroller than the Lite version, with 512 KB of Flash and 128 KB of RAM. It is the same family of microcontrollers as the original MicroPython Pyboard, which provides excellent MicroPython support for the platform.

The PYBStick Standard 26 offers a 26-pin interface.

**On the MicroPython side**, the board can be equipped with the USB connector (type A) allowing direct connection of the board to a computer to be programmed. This product is presented like a USB key ... the memory of the board is presented like a Flash reader thus making it possible to directly edit the Python scripts on the PYBStick. The USB interface also allows the PYBStick to expose a serial port to communicate with the computer as well as an interactive Python command interpreter called REPL.


The REPL command interpreter allows:
* To see the messages displayed by your MicroPython scripts,
* Interact with your scripts during operation (stop the script, inspect the state of variables)
* Test scripts under development (import on the fly with the import command).
* Enter Python instructions to test functionalities of the microcontroller platform interactively.


**On the Arduino IDE side**, simply connect the platform to your computer, place it in programming mode and then start the compilation and upload of your Arduino sketch. Garatronic has provided instructions for installing the Arduino IDE support for the PYBStick.


**Inexpensive and multi-use**

The PYBStick was designed around several key points.
* Oriented towards Makers
* Oriented towards learning and school
* Oriented towards production


The price is low enough not to have to think before including the PYBStick in a project or another.
It is possible to request PYBSticks with the USB not soldered to allow integration into your projects with a minimum obstruction. On the learning side, this allows you to deport the connector, consider putting it in a case or even consider another USB connection.


GPIO connectors have a standard spacing of 2.54mm. This will delight all makers, teachers because it is easy to place the board on a breadboard or a Perfboard. And as the board is 13 pins wide, we are still smaller than a consumer USB stick.


**User interface included**

The board provides three colored LEDs as well as a user button and a DFU button (to update the MicroPython/Arduino firmware but also usable as a user button).


Their use is documented in the MCHobby Wiki (see tutorial section).
Also for professionals


The space between the two rows of connectors corresponds to the DIL dimension of the old EEPROMs. So, you can develop your own boards by providing an already standardized connector. It only remains to connect your PYBStick to it.


The board can be obtained with a non-soldered USB Type-A connector, more suitable for the professional world or the advanced makers ... here which allows to have a very powerful and very compact solution but remaining easy to implement.

**Why a USB Type-A?**

It is true that it seems strange but there are several good reasons for this. 
* Powerbanks have standard USB. So the project can easily be powered by plugging it into a PowerBank.
* USB A allows direct use of the PYBStick as a USB 'mass storage' device, HID device (keyboard, mouse) or serial device (virtual serial port).
* Just put it on the PC or a USB HUB and let's go.
* There is a copy/paste example in the book "[MicroPython et Pyboard](https://www.editions-eni.fr/livre/micropython-et-pyboard-python-sur-microcontroleur-de-la-prise-en-main-a-l-utilisation-avancee-9782409022906)" as well as on the [PYBStick-project GitHub](https://github.com/mchobby/pybstick-projects).
* The USB-A is mechanically very robust, ideal for education/learning where the first manipulations are sometimes rougher.
* Because it is possible to obtain the PYBStick without the welded connector, the user thus conforms to the choice of connector desired for experienced makers.


**Features:**
The PYBStick Standard 26 offers a 26-pin interface (compatible with the Lite version):
* Single core STM32F411 @ 100MHz
* 128 Kio of SRAM
* 512 Kio of Flash (for MicroPython and FileSystem)
* 17x GPIO
  * 8x analog input (ADC)
  * 15x PWM output
  * 3x serial port (UART)
  * 2x I2C bus
  * 2x SPI bus
  * compact size: 28x35mm (without USB), 28x50.5mm (with USB)

Do not forget to insert summary with plateform features like the following (no text, just list).
* 
* 264kB on-chip SRAM
* 8MB external QSPI Flash
* 30 GPIO pins (4 ADC inputs)
* Peripherals
  * 1x UARTs
  * 2x I2C controllers
  * 8x PWM channels
  * USB 1.1 controller
* 3.3V 300mA regulator (580 mA over-current shutdown)
* VIN max 18V
* [ME6215C33 datasheet](http://df.mchobby.be/PYBStick/ME6215.pdf) (voltage regulator)
* [STM32F411RE datasheet](https://www.st.com/en/microcontrollers-microprocessors/stm32f411re.html)


## Purchase
* [Garatronic PYBStick](https://shop.mchobby.be/en/pybstick/1844-pybstick-standard-26-micropython-and-arduino-3232100018440-garatronic.html)

## Contribute

Have some info to add for this board? Edit the source for this page [here](https://github.com/mchobby/micropython-board-catalog/edit/master/_board/{{ page.board_id }}.md).

