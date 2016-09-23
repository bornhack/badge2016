# BornHack 2016 badge contest entries

## The BornHack IoS Badge (Missing wifi and battery) by @-boy
So the idea of this badge hack is to add the ESP8266 Wifi module to the badge to make it part of the Internet of Shit, by also adding a screen and some LEDs the badge will be able to display some info like name or talk info and blink to warn when a new talk is about to take place

Also the plan is to add some tactile buttons for direct user input, one of the buttons will be to make the ESP8266 create a Wifi AP or turn it off if it is on

With 3 input buttons it would also be possible to make a menu system for even more advanced direct user input

The 8x Red LEDs at the top is planned to show the strength of the wifi network the badge is connected to, but can also be used for other things

The 3x Green LEDs are thought to just light up all the time and then blink if the users attention is needed

Besides direct user input, the idea of having it as a IoS device is that it can be reached and configured this way

Also the wifi connectivity is thought as a way for people to send messages to eachother

### Components

* 1x ESP8266 12E
* 1x Arduino Nano
* 2x Green LEDs
* 8x Red LEDs
* 1x OLED display compatible with Adafruit SSD1306 driver
* 3x tactile buttons (not implemented yet)

### Leasons learned and what is working
A couple of things I have learned during the week at BornHack working on the badge hack

* 5v is not 3.3v, this is realy important
* Start with lower goals
* Iterate in small steps with something that works each iteration

Right now the badge can show stuff on the OLED display, but wifi is not working have had some issue with ESP8266 firmware which I worked on most of the week, got basic firmware to work with AT command over serial, so right now the plan is to have a Ardunino to control everything and communicate with the ESP8266 but the Arduino runs 5v so missing components to talk with the 3.3v ESP8266, and lastly it is missing a portable power source and it is quite bulky right now

![The BornHack IoS Badge](https://github.com/at-boy/badge2016/blob/master/images/at-boy/IMG_20160902_184946.jpg "The BornHack IoS Badge")

# BornHack 2016 badge hacks (after the contest finished)


