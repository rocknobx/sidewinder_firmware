# sidewinder_firmware
its the binary stock firmware for sidewinder x2 3d printer

right now its version 2.0.9.3 build under windows 11 with vscode, config comming from marlin repos here on github, so its stock
https://github.com/artillery3d/sidewinder-x2-firmware
https://github.com/MarlinFirmware/Configurations

was building it after didn't found any binary version and crashed my printer with another firmware (but not able to flash TFT...)

flashing is like all howtos out there, use  stm32cubeprogrammer and pronterface under windows, if you didn't try to flash back the 1kb "broken" backup (comming from stm32cube programmer), it should work
