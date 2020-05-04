# GBPocketEmulator

## Summary
In my spare time, I am designing a circuit board that will fit in a Gameboy Pocket shell. It will control the buttons and be used for interfacing a display and Raspberry Pi Zero W. This is a work in progress.

### Components
* Display: Adafruit 2.2" 18-bit color TFT LCD display with microSD card breakout 
  * https://www.adafruit.com/product/1480#technical-details
* Raspberry Pi Zero W
* Game Boy Pocket housing and buttons (from Retro Game Repair Shop)

There are still a more components to be sourced/selected. The major remaining component to be selected is the battery.

### The PCB
The PCB was planned to fit into the Gameboy Pocket housing. This poses a fun challenge as space becomes a constraint. The current plan is to use one large PCB that will have conductive pads for original Gameboy Pocket style buttons. It will also connect the speaker, 3.5mm audio jack, the 2.2" TFT display, and the Raspberry Pi Zero W's 40-pin header. The display and buttons would be connected via the front side of the board, while the remaining components would be connected via the back. 

### Emulator
The current plan for the software is to run RetroPie on the Raspberry Pi Zero W. This will allow for emulation of a fair variety of games and old retro consoles.

### Open Sourcing
I don't have any intention of profitting off of this project. It is just for fun. Therefore, please feel free to improve or modify the designs. I'd appreciate it if you let me know or fork the repository, just so I can know if this project is actually helping other people with their designs. Please don't try to sell this yourself. 
