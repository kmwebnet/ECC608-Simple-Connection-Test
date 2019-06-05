ECC608-Simple-Connection-Test

This communicates ATECC608 secure chip from ESP32 and get infos (serial number, revision number, and current config data),
it helps to make sure the connection between them.

Requirements

  Platformio with VS Code environment.
  install "Espressif 32" platform definition on Platformio

Environment reference
  
  Espressif ESP32-DevkitC
  Microchip ATECC608

Usage

you need to change a serial port number which actually connected to ESP32 in platformio.ini.

Run this project

just execute "Upload" on Platformio. 

License

This software is released under the MIT License, see LICENSE.
