# Manual-EEPROM-Programmer
This is a Programmer Circuit for Manually Programming or Reading EEPROMs

I got the idea from this post but created a layout to fit on a breadboard and added a Socket for the
EEPROM.

http://www.oocities.org/tjacodesign/eeprom/eeprom.html

From Post:

EEPROM programmer manual

The use of the programmer is quite easy, just strictly follow the lists below:
To program data:

SWITCH OFF S1: Data terminals D0--D7 are set as input
INSERT THE EEPROM IN THE SOCKET
SET DATA SWITCHES 0--7
SET ADRESS SWITCHES 0--10
NOW PRESS S2 FOR ABOUT ONE SECOND (GREEN LED ON FOR ONE SECOND)

Now the data is programmed into the EEPROM at this adress. To verify this, you can read the data as described below:

To read data:

SWITCH ON S1: Data terminals D0--D7 are set as output
INSERT THE EEPROM IN THE SOCKET
SET ADRESS SWITCHES 0--10
READ THE DATABITS D0--D7 FROM THE 8 GREEN 3MM LEDS
