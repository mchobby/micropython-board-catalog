# micropython-board-catalog
Maintain data about MicroPython board capable.

# TODO
Here a list of board sheets/pictures to create.

* https://micropython.org/download/
  * PYBD SF3W : __done__
  * PYBD SF6W :
  * adafruit_feather_stm32f405_express : https://www.adafruit.com/product/4382 (Adafruit Feather STM32F405 Express)
  * Nucleo & Discovery
  * Espruino Pico
  * Wipy modules

* TinyPico
  * tinypico_tinypico : https://www.tinypico.com/ (see also https://www.adafruit.com/product/5028 )

* Generic ESP8266
  * adafruit_feather_esp8266 : __done__
  * adafruit_huzzah_esp8266 : __done__
  * olimex_esp8266_dev : __done__
  * olimex_esp8266_evb : __done__
  * to complete for Pimoroni
  * to complete for SparkFun

* Generic ESP32
  * adafruit_feather_esp32 : __done__
  * adafruit_huzzah_esp32 : __done__
  * adafruit_airlift_esp32 : https://www.adafruit.com/product/4201 (update firmware: https://learn.adafruit.com/adafruit-airlift-breakout/upgrade-external-esp32-airlift-firmware )
  * olimex_esp32_devkit_lipo : __done__
  * olimex_esp32_wrover_lipo : https://www.olimex.com/Products/IoT/ESP32/ESP32-DevKit-LiPo/open-source-hardware (to check, 8 MB PsRam)
  * olimex_esp32_iso : https://www.olimex.com/Products/IoT/ESP32/ESP32-POE-ISO/open-source-hardware
  * olimex_esp32_poe : https://www.olimex.com/Products/IoT/ESP32/ESP32-POE/open-source-hardware
  * olimex_esp32_pro : https://www.olimex.com/Products/IoT/ESP32/ESP32-PRO/open-source-hardware (to check, 4 Mio Flash, 4 Mio PSRam)
  * olimex_esp32_evb : __done__
  * olimex_esp32_gateway : https://www.olimex.com/Products/IoT/ESP32/ESP32-GATEWAY/open-source-hardware
  * myduino_hibiscus_sense : https://github.com/CytronTechnologies/MAKER-PI-RP2040/tree/main/Examples/MicroPython
  * to complete for Pimoroni
  * to complete for SparkFun

* garatronic_pybstick26std : __done__
* garatronic_pybstick26lite : https://shop.mchobby.be/fr/pybstick/1830-pybstick-lite-26-micropython-et-arduino-3232100018303-garatronic.html

* RP2040
  * raspberrypi_pico : __done__
  * adafruit_feather_rp2040 : __done__
  * adafruit_itsybitsy_rp2040 : __done__
  * arduino_nano_rp2040 : https://blog.arduino.cc/2021/01/20/welcome-raspberry-pi-to-the-world-of-microcontrollers/
  * pimoroni_pico_lipo : __done__
  * pimoroni_tiny_2040 : __done__
  * pimoroni_keybow_2040 : https://shop.pimoroni.com/products/keybow-2040
  * pimoroni_picosystem : https://shop.pimoroni.com/products/picosystem
  * sparkfun_pro_micro_rp2040 : https://www.sparkfun.com/products/17717
  * sparkfun_thing_plus_rp2040 : __done__
  * sparkfun_micromod_rp2040 : __done__

* Pycom Boards
  * pycom_wipy3 : https://pycom.io/product/wipy-3-0/  (support aussi ESP32 Lobiris)
  * pycom_sipy : https://pycom.io/product/sipy/
  * pycom_lopy4 : https://pycom.io/product/lopy4/
  * pycom_gpy : https://pycom.io/product/gpy/
  * pycom_fipy : https://pycom.io/product/fipy/

* Micro:bit 1 & 2

* DFRobot boards
  * to complete

* Cytron.io
  * cytron_maker_pi_rp2040 : __done__


* M5Stack boards (ESP32 & TinyPico based)
  * m5stack_core_basic : __done__
  * m5stack_core_gray : __done__
  * m5stack_core_face_kit : __done__
  * m5stack_m5go : __done__
  * m5stack_core_fire : __done__
  * m5stack_core2 : https://docs.m5stack.com/en/core/core2
  * m5stack_m5stickc : https://docs.m5stack.com/en/core/m5stickc (ESP32-Pico)
  * m5stack_m5stickc_plus : https://docs.m5stack.com/en/core/m5stickc_plus (ESP32-Pico)
  * m5stack_atom_lite : https://docs.m5stack.com/en/core/atom_lite
  * m5stack_atom_matrix : https://docs.m5stack.com/en/core/atom_matrix
  * m5stack_atom_echo : https://docs.m5stack.com/en/atom/atomecho
  * m5stack_core2_aws : https://docs.m5stack.com/en/core/core2_for_aws
  * m5stack_core_ink : https://docs.m5stack.com/en/core/coreink

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
  * garatronic_pyb405 : __done__ _Why not dayly build?_
  * Adafruit_F405_Express : _why not dayly build?_
  * HYDRABUS
  * B_L072Z_LRWAN1
  * B_L475E_IOT01A
  * CERB40
  * NetDuino plus 2
  * MIKROE_CLICKER2_STM32
  * LIMIFROG
  * LIMIFROG

# Data organization
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
