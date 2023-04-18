
# TFT screen with encoder basic test

Starter kit based on Platformio for handling TFT screen with encoder on ESP32 (no s3). Note that SPI wiring use Hardware SPI with dedicated pins.

## Files

Choose among files which test to start with. Rename file to main.cpp to run PIO commands

- main.encoder : for basic serial printing of encoder with pushbutton
- main.screen : for TFT screen with benchmarks for several config
- main.menu : includes two previous features with a menu generated with tcmenu, it uses encoder to navigate

## Keywords

**HW:** ESP32, 2.8" TFT screen, encoder with push button switch, ILI9341 controller

**SW:** platformia, tcmenu, Adafruit_ILI9341

