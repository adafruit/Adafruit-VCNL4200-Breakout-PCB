## Adafruit VCNL4200 Long Distance IR Proximity and Light Sensor - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6064"><img src="assets/6064.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VCNL4200 Long Distance IR Proximity and Light Sensor - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6064

### Description

We've all been there. That thing is close but how close? When you need to measure a meter-or-so distance with reasonable accuracy, the VCNL4200 Long Distance Proximity Sensor from Vishay can do that for you. It's excellent for robotic or motion-detection situations. And. if perchance you also needed to measure the amount of light at the same time, you're in luck! The VCNL4200 can do that too, with it's built in ambient light sensor (ALS)

The VCNL4200 is a powerful two-in-one sensor, with a proximity sensor that works from 0 to 1.5m (59 inches) and light sensor with range of 0.003 to 1570 lux. It's the longest-range IR distance sensor we've seen other than the Sharp Analog distance sensors, and at a great price with I2C interface. Note that while the chip itself is specced for 1.5 meter distance measurements, that depends a bit on optimal lighting situations and high power configuration. We've found that 50-100cm is a good range to expect, and you won't get a lot of accuracy/precision as the detection object gets farther away. We normally suggest ToF sensors for long precision measurements, but sometimes you want the low cost and simplicity of infrared. Also, you get a 'free' light sensor which ToF sensors don't contain.

"OK, finally I can get started on my proximity and light sensing project, but how do I use it?" you say. To make life easier so you can focus on your important work, we've taken the VCNL4200 and put it onto a breakout PCB along with support circuitry to let you use this little wonder with 3.3V (Feather/Raspberry Pi) or 5V (Arduino/ Metro328) logic levels. Additionally since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro and you can use our CircuitPython/Python or Arduino drivers to easily interface with the VCNL4200 and make approximate approximations of proximity in no time! QT Cable is not included, but we have a variety in the shop. 

To give you some ability to tune your measurements for your situation, the VCNL4200 lets you adjust the integration time for both light sensing and proximity, IR LED power, duty cycle, multi-pulse, and sunlight-immunity. There's also interrupt output support for light or proximity measurement thresholds.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
