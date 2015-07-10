examples
========


yksEEinit#
----------

Change the AES-128 key, the public and private ids and the static password to your personal likings (and keep them private).
Upload the code to your Teensy to initialize the EEPROM. This needs to be done only once.


yksTouch1
---------

Upload the code into your Teensy and stick an ordinary paper clip into pin D7.
This will turn your Teensy into an USB keyboard that emits keyboard scan codes whenever you touch the paper clip.
Every time you touch the paper clip for a short time, a unique new Yubikey compatible OTP will be 'typed' by the Teensy.
If you press the paper clip for a longer time, the static, secret password will by 'typed' by the Teensy.



