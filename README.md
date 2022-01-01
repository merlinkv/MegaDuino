<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* You may not use the material for commercial purposes.
* You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

# ATTENTION

This project was made for the retro community and not for commercial purposes. So only retro hardware forums and individual people can build this project.

ITS SALE ON EBAY OR OTHER AUCTION SITES IS PROHIBITED

# Note

I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

# MegaDuino 4.7

An improved versión of the initial MegaDuino project started by me on September 2019.

MegaDuino is an evolution of other projects like TZXDuino and CASduino but it's based on the Arduino Mega 2560 Pro Embed board.

MegaDuino works with my **MegaDuino Firmware** version, a modification of the MaxDuino firmware specially developed for Arduino Mega 2560 family boards,
OLED 128x64 1.3" (64 rows) & LCD 20x4 screens, it also add an extra button for Reset or future purpouses. MaxDuino firmware from rcmolina can be used as well.

MegaDuino it's a digital cassette tape player that allows the load of games and applications on retro computers, mainly 8-bit computers such as the
ZX Spectrum, Amstrad CPC and others.

A special thanks to Alfredo (acf76es), without his help this update would not have been possible.

Original firmware based on developments by Andrew Beer, Duncan Edwards, rcmolina and others.

**MegaDuino** has been tested on **ZX Spectrum**, **Amstrad CPC**, **MSX**, **Oric Atmos**, **Dragon**, **Tandy Coco**, **Acorn Electron**, **BBC-Micro**, **ZX80** & **ZX81** computers.

Board revisions and notes

**01-01-2022 - MegaDuino 4.7**

* Removed external power jack & led.
* Added a 4 rows piano switch to allow selection of 3.5mm audio and remote cables to be used:
  - **AUDIO**
    * 1-2 OFF -> L - ON / R - OFF / GND - ON
    * 1 ON / 2 OFF -> L+R - ON / GND - ON
    * 1 OFF / 2 ON -> L - ON / R+GND - ON
  - **REMOTE**
    * 3-4 OFF -> REM (L) - ON / R - OFF / GND - ON
    * 3 ON / 4 OFF -> REM (L)+R - ON / GND - ON
    * 3 OFF / 4 ON -> REM (L) - ON / R+GND - ON
* Added footprint to add an ICSP connector (optional) to allow use the Mega 2560 as master/slave board without opening the case.


**05-10-2020 - MegaDuino PM 1.3**
  * All capacitors & resistors are SMD
  * Added Buzzer circuitry to allow listening the loading sounds directly from MegaDuino. Can be activated or deactivated.
  * Added 3mm leds for External Power, USB Power, Amplifier ON, Amplifier OFF & Buzzer ON/OFF
  * Amplifier & Buzzer gain can be selected (Amplifier 20, 50 & 200 - Buzzer 20 & 50) by jumpers
  * Two Remote connectors 2.5mm & 3.5mm to allow all connection possibilities
  * Removed ICSP pins

**16-05-2020 - MegaDuino 2.9**

* Reworked amplifier schema and added a DPDT slide switch to completely separate signal when the amplifier is ON or OFF.
* Reworked connections of the Audio OUT jack to allow use of stereo or mono cables without need to modify them. Also eliminates undesired signals.
* Removed extra 5v & 3.3v pins
* ICSP pins moved to a better position to allow program the Mega 2560 or use master/slave boards without opening the case.

**11-04-2020 - MegaDuino 2.8**

* Jumpers added to allow selection of signal gain. Now it's possible to select between 50 and 200.

Links:

* https://www.winuaespanol.com/phpbb3/viewtopic.php?p=2844#p2844
* https://www.winuaespanol.com/phpbb3/viewtopic.php?p=6217#p6217
* https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=8496#p150210





