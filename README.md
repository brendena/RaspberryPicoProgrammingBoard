# boards
## PicoProbeProgrammerBoard

A board to help with programming and debugging the raspberry pi pico.  I have a standard 2x5 pin connector that can carry swd, power and some extra debug signals

connectors 
* 1.27mm 2x5 Pin 10 Pin SMT
* 2.54mm 7 pin breakout jtag
* 3 1.0mm jst connector - used on the pico with that comes pre soldiered


## PicoDebugInterface

This is a small board that sites ontop of the main raspberry pi pico to add a 2x5 pin connector ontop to make it easier to program with the option to add extra debug pin as well.


# RaspberryPi_PicoProgrammer

This board will make programming the pico a little cleaner.  It shares most of the features that the PicoProbeProgrammerBoard has.  But with the added benifit have being able to directly read the i2c's or debug connections while directly from the pi.

* Potentially very usfull with a right angle for the pi 4000.  So you can easily add debugging ability to that board.