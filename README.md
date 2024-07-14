# Tair Keyboard
The Tair keyboard is a split 72-key fully wireless keyboard with 6x6 column staggered keys (with 3 thumb keys) based on an Nordic nRF52840 microcontroller (nice!nano v2).

It uses ZMK Firmware (based on Zephyr RTOS) for functionality. This allows the keyboard to operate wirelessly and handle multiple keypresses simultaneously.

![Tair v1](https://raw.githubusercontent.com/yazansrayyes/Tair-Keyboard/blob/main/assets/v1.heic)


# Flashing Firmware
The nice!nano v2 is the Adafruit nRF52 Bootloader. To jump into the bootloader all you need to do is double tap reset. This can be done by double tapping RST and GND pins on the nice!nano quickly. 

Once connected to your computer using USB and put into bootloader mode, the nice!nano will show up as a storage device.After building the project, a .uf2 firmware file will be generated. To flash, simply drag and drop the .uf2 to the storage device.

