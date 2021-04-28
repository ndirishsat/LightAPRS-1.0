This file adds options for larger I2C/TWI and serial buffers for ATMega1284.
It can use A LOT of RAM, so use with caution!


Place this file in the same directory as the MightyCore boards.txt file.
You can find that file's location by going to:
"File->Preferences" then go to the directory at the bottom of the Window.
For example, on linux, it is /home/showard/snap/arduino/56/.arduino15/

Then navigate to
packages/MightyCore/hardware/avr/{VERSION_NUMBER}

You should find boards.txt there. Copy this boards.local.txt in to that folder.
Restart Arduino. You now should have extra options in the MightyCore menus.
