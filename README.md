# Luftdaten-ESP8266-Flasher
These are shell scripts that help us flash our sensors faster and more reliably.

## flash.sh
This script will download the latest firmware from luftdaten (madavi server) and flash this to the connected ESP8266 NodeMcu chip

## getId.sh
This script will show you the chip_ID from the NodeMcu. It also selects the correct Serial port.

## Requirements

[Esptool](https://github.com/espressif/esptool). There are several ways to install it.

On Linux, easiest installation is through a package manager. Ubuntu: `sudo apt install esptool`
