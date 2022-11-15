# VGM Player for SN76489 with Arduino Uno
this edited version uses built in oscilator in arduino uno and nano, and each LED has its own pin
to add your own VGM, go to hexed.it, upload your VGM, and copy it whole except the header (the header ends with lot of dots consecutively), right click and select export selected bytes as code snipet, copy the hex data and replace the hex data in the .ino with it

VGM player to reproduce video game music in the original hardware used in the videoconsoles. 

This project is related to the sound chip SN76489 that has 4 four channels (3 for square waves and 1 for noise). This chip was used in the Sega Master System and Game Gear.

Project Schematic:
![Alt text](schematic.png?raw=true "Title")
Note: you need to connecting pin next to audio output to ground, or it will not work!!!
