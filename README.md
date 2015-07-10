arduino-yksim
=============

Simulate Yubikey with Teensy (Tested on Teensy 3.0)


How-to use
----------

Merge the libraries and examples directories with your arduino-1.6.X installation. Set USB type to Serial + Keyboard + Mouse + Joystick.

Start the Ardunio GUI and open one of the yksEEinit files (in File --> Examples --> YKS).
Change the AES-128 key, the public and private ids and the static password to your personal likings (and keep them private).
Upload the code to your Teensy. This needs to be done only once.

Then open the file yksTouch1 (also in File --> Examples --> YKS) and upload this code to your Teensy.

Have Fun !
----------

