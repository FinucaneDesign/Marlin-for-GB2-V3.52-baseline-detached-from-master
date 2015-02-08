# Marlin-for-GB2-V3.52-baseline-detached-from-master
This is the baseline we have been using for all Gigabots out the door of our Houston assembly facility. Supports our heated bed, Viki LCD remote, SD card support, and current entstop configuration. Some forking will occur here to support other features, but work is progressing on re-forking from Marlin's master repo. Stay tuned!

For this fork, the Viki 2.0, or miniViki, will be used. Many modifications are made per these instructions on the Panucatt website:
http://panucattdevices.freshdesk.com/support/solutions/folders/1000183232

Before compiling the Marlin Firmware, one must download the following library from here:
https://bintray.com/olikraus/u8glib/Arduino
...and then install it in their Arduino/Libraries file. Once there, you can confirm it is visible to the Arduino IDE by navigating to "File/Sketchbook/Libraries/U8glib". If it is not there, check that you are opening the same version of Arduino which you installed the library in, and then close and restart Arduino.
