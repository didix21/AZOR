# AZOR
This repository contains all the AZOR 1.0 board KiCad files.  

## About Hardware 

AZOR 1.0 is based on [DUET 0.85](http://reprap.org/wiki/Duet#Drive_numbers) created by [dc42](https://github.com/dc42). I have done very important modifications as delete Ethernet and micro SD ports. Instead, I have added a USB 2.0 port to read USB Sticks. 

Moreover, the integrated steppers A4982 have been deleted and instead of that, I have placed HEADER PINS to connect drivers as A4988 or DRV8825. 

## About Software 

AZOR 1.0 use [Marlin4Azor](https://github.com/didix21/Marlin4AZOR), it is a modified version of work  done by [Wurstnase](https://github.com/Wurstnase). In other words it is based on [Marlin4Due](https://github.com/Wurstnase/Marlin4Due).

## License

Marlin is published under the [GPL license](LICENSE).




