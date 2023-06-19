# S3BareBone

![Arduino Tools](/KiCad/s3Barebone-brd.PNG)

S3 Bare Bone is, as the name implies, is a very minimal ESP32 S3 deveopment board.  Only a 3.3v regulator, some passive devices and a few buttons are included on the board.
All the pins of the ESP32 S3 are exposed on the pin headers on each side giving 100% access to the device.

The 8MB version of the ESP32 S3 is on the baord.

## Power
Power can be supplied via the USB connector or via the 5v or 3.3v pins...**Never both at the same time though**.

## Arduino
To upload sketches to the board via the USB connector, set the following:

![Arduino Tools](/images/arduino_board.PNG)

Sketches can also be uploaded via an ISP programmer using the RX/TX pins.  If an external programmer supplies 5v, this can be connected to the 5V pin to power the board.  Just don't power supplied via the USB at the same time.
You can have the USB connected and supplying power as long as power is not also supplied via the ISP.

Hope that makes sense.

The board will be available on Tindie.com shortly.

18-June-2023



