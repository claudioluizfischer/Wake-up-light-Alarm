﻿# Wake-up-light-Alarm

> ⚠ Status: Upgrading

## This is the software used to program a soundless alarm using an Arduino.

### This is how the hardware looks like:

![image](https://user-images.githubusercontent.com/77110029/168192792-596cd04c-8460-43b6-89f6-41ad7330e712.png)

## The input is made by the user typing on the keypad:

+ The current time
+ The desired time to wake up

## This is how the soundless alarm works:

1) After the input is done, the current time is increased through a loop until the two times are the same.

2) When the current time is igual to the desired wake-up time, the LEDs in the strip of the NeoPixel ring start to turn on gradually. Theirs intensity is also incresed as the time passes. 

3) When the user wakes up, in order to turn the LEDs off, all the user has to do is to select the '*' on the keypad.

4) After turning it off, the user has the option to put another new current time and alarm time or the user can turn it on back again running the program again.

5) Make sure you are using the Arduino IDE in order to run this program. Check the hardware before implementing the program.
