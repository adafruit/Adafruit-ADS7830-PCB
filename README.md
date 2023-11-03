## Adafruit ADS7830 8-Channel 8-Bit ADC with I2C - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/5836"><img src="assets/5836.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ADS7830 8-Channel 8-Bit ADC with I2C - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5836

### Description

Many microcontrollers have ADCs these days, for reading analog/resistive sensors like potentiometers, thermistors, LDR light sensors, etc. but sometimes you need MOAR! Or maybe you're using a single board computer like a Raspberry Pi that has no ADCs at all!

The Adafruit ADS7830 8-Channel 8-Bit ADC with I2C is an affordable 8-channel ADC with I2C interface, so it's easy to include with any platform. Wire up to the SDA/SCL pins plus power and ground, only four wires required. If you need more than 8 channels, there's 2 address pins so you could have 4 x 8 = 32 total ADC channels with chain-able Stemma QT cables.

Note that this chip isn't the fanciest ADC on the market: you can get up 70 Ksamples per second (you'll need 3.4MHz I2C speed support for max speed rate), and only 8-bits of resolution, so it's good for rough sensor measurements. For example, this would definitely be a great way to add a ton of potentiometers or flex sensors to a build, but wouldn't be a good match for precision thermistor conversion.

To use it, check out our Arduino library which will quickly let you read from any of the 8 channels as single ended inputs - or you can use differential mode which will use two adjacent pins for the positive and negative references. You can power the board from 3 or 5V power and logic, which will also act as the reference voltage and pullup voltage. Or you can change the reference voltage by cutting the jumper on the back and wiring to the breakout pad, as long as it is less than the power supply.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the ADS7830 or to chain it with a wide range of other sensors and accessories using a compatible cable.

QT Cable is not included, but we have a variety in the shop.

Comes with a bit of 0.1" standard header in case you want to use it with a breadboard or perfboard.  Four mounting holes for easy attachment.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
