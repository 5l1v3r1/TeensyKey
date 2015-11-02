# TeensyKey v1.0 #

This is based on [pagong's arduino-yksim](https://github.com/pagong/arduino-yksim).

## Introduction ##

**TeensyKey** is an implementation of Yubico software running on Teensy hardware. This project aims to simulate the YubiKey on Teensy (Tested on Teensy 3.0) and provide similar two-factor authentication functionality.


## Installation ##
To use **TeensyKey**:  
- Go to https://github.com/cr7pt0/TeensyKey, click the **Download ZIP** button and save the ZIP file to a convenient location on your PC.
- Uncompress the downloaded file.  This will result in a folder containing all the libraries and examples.
- Copy all folders to the Arduino sketchbook\libraries folder.
- Set USB type to Serial + Keyboard + Mouse + Joystick.

## Examples ##
The following example sketches are included:
- **yksEEinit:** Change the AES-128 key, the public and private ids and the static password to your personal likings (and keep them private).
Start the Ardunio GUI and open one of the yksEEinit files (in File --> Examples --> YKS).

Upload the code to your Teensy. This needs to be done only once.

- **yksTouch1:** Then open the file yksTouch1 (also in File --> Examples --> YKS) and upload this code to your Teensy.

In order to use you can touch the A9 pin with your finger, stick an ordinary paper clip into pin A9, or put together a custom button.

Since this uses the capacitive touch feature of the Teensy all that is needed is to physically contact pin A9.

Touch for less than 1 second for YubiKey One-Time Password, more than 1 second for static password.

For more information on YubiKey One-Time Password see [yubico technical description] (https://www.yubico.com/products/yubikey-hardware/yubikey-2/technical-description/) .


