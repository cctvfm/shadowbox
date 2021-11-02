# shadowbox
Shadowbox is an Open Source optically controlled digital drone synth where parameters are controlled by introducing or blocking light. Based on Emilie Gillet's Plaits Module.

![Main PCB](https://github.com/cctvfm/shadowbox/blob/main/art-export.png)


To Compile code:

Copy entire 'neuzplaits' folder into the 'eurorack' folder in the mutable dev environment.

run 

make -f neuzplaits/bootloader/makefile hex

make -f neuzplaits/makefile



to upload using ST-Link V2:

make -f neuzplaits/makefile upload

'AVR CHICLET' is an alternate brain board using ATMEGA328P. Code to come.
