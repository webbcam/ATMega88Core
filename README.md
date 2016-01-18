# ATMega88 Core

This Core is built much off of SpenceKonde's ATTinyCore
(https://github.com/SpenceKonde/ATTinyCore)
And the ArduinoCore for ATMega168  

This core will allow you to upload sketches onto your ATMega88  
using the Arduino IDE

# Installation Instructions
1)  Clone this repository into your Arduino/hardware folder  
    (if the hardware folder does not exist, create one)
2)  Restart Arduino IDE

# Use
In the Arduino IDE, select Tools > Board and under "ATMega Chips" 
select ATMega88. You can then select the Brown Out Detection (B.O.D),  
and the Clock Source

## Notes:  
  You will need to select the correct Programmer under Tools that you  
  are using. I have only tested it with a USBTiny Programmer

  Also, when burning the bootloader onto the chip, you will need to  
  use a 16MHz external clock/crystal.
