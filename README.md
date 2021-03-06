# A lightweight, cross-platform Modbus library
[![The GPL license](https://img.shields.io/badge/license-GPL-blue.svg?style=flat-square)](http://opensource.org/licenses/GPL-3.0)
[![Travis CI](https://img.shields.io/travis/Jacajack/liblightmodbus/master.svg?style=flat-square)](https://travis-ci.org/Jacajack/liblightmodbus)
[![Coveralls](https://img.shields.io/coveralls/Jacajack/liblightmodbus/master.svg?style=flat-square)](https://coveralls.io/github/Jacajack/liblightmodbus)

<br>[Liblightmodbus on launchpad...](https://launchpad.net/liblightmodbus)

`liblightmodbus` is a very lightweight, highly configurable, platform-independent Modbus RTU library.

## Features
- Minimal resources usage
- Relatively easy to use
- Supports all basic Modbus functions and allows users to define thier own Modbus function handlers
- You can pick specific modules, you want to be included during customized build process
- Supports register/coil access callback functions

*Currently supported functions include: 01, 02, 03, 04, 05, 06, 15, 16 and 22.*
Check out the [online documentation](https://jacajack.github.io/liblightmodbus/) for more technical information and user guide.

If you need help - [email me](mailto:mrjjot@gmail.com). If you want to help - contribute here, on Github. **All contributions are welcome!**

## Platforms on which liblightmodbus is known to run
 - 8-bit AVR (ATmega 8, ATmega 328, etc.)
 - STM32 ARM (STM32F103, STM32L151, etc.)
 - Raspberry Pi
 - i386, amd64
 - PowerPC

## PPA
On Ubuntu/Debian `liblightmodbus` can be obtained from [PPA](https://code.launchpad.net/~mrjjot/+archive/ubuntu/liblightmodbus) (Personal Package Archive).

This is how to install it:
 - Add PPA to your system - `sudo add-apt-repository ppa:mrjjot/liblightmodbus`
 - Update software lists - `sudo apt-get update`
 - Install development package - `sudo apt-get install liblightmodbus-dev`
