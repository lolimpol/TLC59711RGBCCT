# TLC59711 RGB + CCT library

<a href="https://www.adafruit.com/product/1455"><img src="assets/board.jpg?raw=true" width="500px"></a>

This is the Adafruit 12-Channel 16-bit PWM LED Driver - SPI Interface - TLC59711

This library is a modification of the Adafruit TLC59711 library, adding functions for RGB + CCT applications. Check out the original library for normal RGB LED's.
Every LED uses **6 channels** to prevent spreading one LED over multiple chips, like: <br>
Channel 6 being R of LED 1 <br>
Channel 7 being G of LED 1 <br>
Channel 8 being B of LED 1 <br>
Channel 9 being CW of LED 1 <br>
Channel 10 being WW of LED 1 <br>
Channel 11 being R of LED 2 <br>
Channel 12 being G of LED 2 <br>
Channel 1 of the next TLC59711 being R of LED 2 <br>

Instead we skip the 6th channel only allowing 2 LED's per chip. 

Adafruit license text:

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried (Adafruit Industries). 
BSD license, check license.txt for more information
All text above must be included in any redistribution
