# micropython-board-catalog
Maintain data about MicroPython board capable.

# TODO
Here a list of board sheets/pictures to create.

* https://micropython.org/download/
  * PYBD SF3W & SF6W
  * adafruit_feather_stm32f405_express : https://www.adafruit.com/product/4382 (Adafruit Feather STM32F405 Express)
  * Nucleo & Discovery
  * Espruino Pico
  * Wipy modules
  * Generic ESP8266 , ESP32
  * TinyPico
* garatronic_pybstick26std : __done__
* garatronic_pybstick26lite : https://shop.mchobby.be/fr/pybstick/1830-pybstick-lite-26-micropython-et-arduino-3232100018303-garatronic.html
* RP2040
  * raspberrypi_pico : __done__
  * adafruit_feather_rp2040 : __done__
  * adafruit_itsybitsy_rp2040 : __done__
  * arduino_nano_rp2040 : https://blog.arduino.cc/2021/01/20/welcome-raspberry-pi-to-the-world-of-microcontrollers/
  * pimoroni_pico_lipo : https://shop.pimoroni.com/products/pimoroni-pico-lipo
  * pimoroni_tiny_2040 : https://shop.pimoroni.com/products/tiny-2040
  * pimoroni_keybow_2040 : https://shop.pimoroni.com/products/keybow-2040
  * pimoroni_picosystem : https://shop.pimoroni.com/products/picosystem
  * sparkfun_pro_mico_rp2040 : https://www.sparkfun.com/products/17717
  * sparkfun_thing_plus_rp2040 : https://www.sparkfun.com/products/17745
  * sparkfun_micromod_rp2040 : https://www.sparkfun.com/products/17720
* Picom Boards
* Micro:bit 1 & 2
* Olimex ESP32 / 8366 boards
* Adafruit ESP32 / ESP8266 board
* DFRobot boards
  * to complete
* M5Stack boards (ESP32 & TinyPico based)
  * to be complete
* Risc-V boards
  * MAixDuino (support machine API)

__from MicroPython/ports__
Look of some boards are already compatible with MicroPython. Is automatic compilation can be foreseen for them?
* samd : some work started
* teensy : __why not dayly build?__
* Zephyr : Looks important
* mimxrt
* nrf
* pic16bit
* powerpc
* rp2 : Raspberry-Pi
* stm32
  * Olimex_E407 
  * NADHAT_PYBF405 : DONE. __Why not dayly build?__
  * Adafruit_F405_Express : __why not dayly build?__
  * HYDRABUS
  * B_L072Z_LRWAN1
  * B_L475E_IOT01A 
  * CERB40
  * NetDuino plus 2 
  * MIKROE_CLICKER2_STM32
  * LIMIFROG 
  * LIMIFROG 

# Remarks
__board_id__:

The __board_id__ is a __unique board identifier__ used to name several ressourses about a given board.
The identifier may already be listed down here upper.

It is composed as follow:
* lowercase only (a..z, 0..9, _)
* underline (_) is the only special characters used.
* Named as follow: <manufacturer>+"_"+<board_identification_code> . 
* Manufacturer is one word only. Please keep unique manufacturer code. Eg: garatronic, olimex, adafruit, pycom.
* board_identification_code can contains several word, "_" is used as space. E:. pybd_sf2w

__board file__:

copy the template.md to _board/<board_id.md>

Fill-up the target file. 

__Images__:

* /assets/images/boards/large : contains board jpeg @ 800 x 600px. Named with <board_id.jpg>
* /assets/images/boards/small : contains board jpeg @ 300 x 225px. Named with <board_id.jpg>
