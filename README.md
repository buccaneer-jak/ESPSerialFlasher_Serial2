[![Arduino Badge](https://github.com/winner10920/ESPSerialFlasher/actions/workflows/check-arduino.yml/badge.svg)](https://github.com/winner10920/ESPSerialFlasher/actions/workflows/check-arduino.yml)
[![Compile Badge](https://github.com/winner10920/ESPSerialFlasher/actions/workflows/compile-examples.yml/badge.svg)](https://github.com/winner10920/ESPSerialFlasher/actions/workflows/compile-examples.yml)
# ESP32 Serial flasher using Serial2

## Overview
Provides the ability to flash an ESP32 from another ESP32 via Serial2

## Limitations
Has only been confirmed to work on the Espressif ESP32 dev Board. With the correct ino.bin this has successfully flashed other ESP32, ESP32-C2 and ESP32-S3 boards
This library is edited by myself with limited knowledge of the underlying ESP Flasher code, it's basically an Arduino port of the espressif flasher (https://github.com/espressif/esp-serial-flasher) . It's worked well for me but there are no guarantees and I welcome other people to help contribute to make this more refined and more usable for the general public

## Requirements
An Espressif ESP32 dev board with an sd card attached to standard SPI pins. Uses the SD library included with the arduino IDE.

## Example
TODO: Obviously the image below is from the original commit which I need to change.

Below is a screenshot from the Download and flash example
Demonstrates updating from Nina firmware version 1.4.6 to 1.4.7 in the same program
<img src="img\DownloadAndFlash.png" width="auto" height="auto"> 


## Dependencies
  - [SD](https://github.com/arduino-libraries/SD)

## Licence

Code is distributed under Apache 2.0 license.

## Credits
This Library is based off of code from (https://github.com/espressif/esp-serial-flasher)

## Contact Me
If you have any Questions, Comments, Concerns please email me @hotmail.com
