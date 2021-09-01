

This project uses Circuit Python to recreate the original Macropad pre-installed demo.ino.

Files:
- demo.ino - original demo code
- code.py - main source that should be installed in mounted CIRCUITPY directory
- circuitpython_libs - lib files etc for mounted CIRCUITPY directory to support lib references


## Background on Macropad

[MacroPad Overview](https://learn.adafruit.com/adafruit-macropad-rp2040/overview)

The pre-installed application source code is in the file 'demo.ino'.  

Some notes on using the demo:
- seems like I had to re-add the includes for Adafruit_SH110X.h, Adafruit_NeoPixel.h, RotaryEncoder.h
- to load code, need to unplug usb and hold button.  Maybe reset + button will work?
- uncommenting the 'tone' calls seems to hang the board


[Macropad Example on Github](https://github.com/adafruit/Adafruit_Learning_System_Guides/tree/main/Adafruit_MacroPad)

[Other Macropad Example on Github](https://github.com/adafruit/Adafruit_CircuitPython_MacroPad/tree/main/examples)

[Other Examples on Github](https://github.com/adafruit/Adafruit_Learning_System_Guides)

## TODO List
- [done] setup and create tone
- [done] comment out tune
- [done] build display
    - anchor_point vs anchor_position?
    - title
    - rotary
    - direction
    - 12 keys
- [done] pixel colors
- [done] button press for brightness
- [done] comment with demo.ino?
- [done] refactor and clean up python
- [done] how to run a clock

NOTE: I2C documentation at: https://github.com/adafruit/Adafruit_CircuitPython_SSD1306

