# SoundBerry
## By Concord High School Group C.3.8
2025-2026
## Ahmed El Mashad and Charlie Iannetta
### Raspberry Pi based soundboard for the Indian River School District in Delaware. This repository will hold a python script as well as sound files for our Raspberry Pi 3 B running PIOS
# Requirements to create your own Soundberry
  1. Raspberry Pi (atleast Pi 3) with Raspberry Pi OS Installed (Previously Raspbian).
  2. One Arduino or equivilant microcontroller that uses C++
  3. A Computer
  4. 10 Buttons, 1 3 pin analog switch, a 3.5mm aux jack
  5. Wires and a breadboard to connect everything
  6. 11 1k ohm resistors


# Arduino Setup
1. Copy the code from the file "SBarduinocode.txt" over into your arduino code editor and send it over
2. Take your Arduino and wire your breadboard to look like "ArduinoWiring.png" or "Soundberry Schematic.pdf" (up to you which you follow).
3. Connect your arduino back to your computer and open up the serial terminal.
4. Make sure the arduino is sending over numbers 1-20. (You will need to flip the switch to access the second set of numbers)
5. Make sure the random button (the button on the far right of the breadboard on "ArduinoWiring.png") is sending a random number between 1-20 every press.
6. (Optional Step, only do if you have a 3.5mm aux button) Replace random button with ypur 3.5mm aux jack, wiring the plus and minus sides of the aux to where the button sat.
7. Move onto the Raspberry Pi Setup

   
# Raspberry Pi Setup
1. (Optional but recommended) Using a flash drive, copy "PiCode.txt" over to your PiOS install (or type it manually its up to you)
2. 
