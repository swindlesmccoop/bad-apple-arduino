# Info
This is highly adapted from https://github.com/P0keDev/Midi2Arduino, I just did all of the random hard work because the instructions were hard to understand. If I'm not too lazy, I'll fork it in the future and fix it up to be noob friendly.

# Prerequisites:
Arduino IDE, but not the Windows Store version. If in doubt, just use Linux.
Get it here: https://www.arduino.cc/en/software
***DO NOT GET THE WINDOWS APP!***

# Parts List
* Arduino Mega or off-brand equivalent
* Standard size breadboard
* 1 Resistor of any ohm
* 6 Piezo Buzzers
* A bunch of wires
* Button

# Setup/Instructions

## From https://github.com/P0keDev/Midi2Arduino
  Install the ToneLib library (libraries/ToneLib) as you would any 3rd party library.
  Navigate to C:\Program Files (x86)\Arduino\hardware\arduino\avr\cores\arduino and remove Tone.cpp (this is important!) I suggest backing up Tone.cpp to another  location if you ever want it again. If you delete it completely, you'll have to reinstall the Arduino IDE to get it back.

## From me
1. Download this repo
2. Open up the `badapple` folder
3. Open up `badapple.ino`
4. Push it to your board

## Picture
![alt text](https://github.com/swindlesmccoop/bad-apple-arduino/blob/main/wiring.png?raw=true)
