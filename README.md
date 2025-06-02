## Adafruit INA237 85V 10A 16-bit DC Current Voltage Power Monitor - STEMMA QT PCB

<a href="http://www.adafruit.com/products/6340"><img src="assets/6340.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit INA237 85V 10A 16-bit DC Current Voltage Power Monitor - STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6340

### Description

The INA237 is an amazing power monitoring chip, with best-of-everything support: up to 85VDC common-mode, high or low side measurements, 16-bit ADC for precision measurements from milliamp to Amp, and I2C interface for easy configuration of alerts, oversampling, gain adjustments and more!

The INA237 is similar to the INA228, with the same:

* up to +85V high or low-side measurements
* up to 10A or 2.75A
* current, voltage and power measurements

However, unlike the INA228 the INA237:

* has only 16-bit resolution, so 0.15mA or 42uA LSB rather than 10uA/2.5uA
* the INA228 can measure energy/charge for you but the INA237 cannot
* 0.3% gain error, ±50 µV max offset voltage compared to INA228's 0.05% gain error, ±1 µV

This breakout board may well be the last current sensing solution you every need to buy. Not only can it do the work of two multimeters, but it can do it with amazing precision and flexibility. With it you can measure high or low side DC current, the bus voltage, and have it automatically calculate the power. It can do so over impressive voltage, current, and temperature ranges with better than 1% accuracy, all while delivering the data in an easy to use format over I2C.

Works great with any microcontroller that is CircuitPython or Arduino compatible as well as single board computers such as the Raspberry Pi. It is compatible with 3V or 5V logic and can measure bus voltages up to +85VDC. Not for use with AC voltages.

Most current-measuring devices operate with some notable constraints that limit what they can be used for. Many are low-side only which can cause issues as the ground reference changes with current. Others like its little sister the INA219B avoid this by measuring on the high side but need to change their shunt resistor to measure different current ranges. The INA237 avoids these limitations, and with the precision 15milliohm shunt resistor on board, it can be used to measure as much as +85V at up to 10A (~0.15mA per LSB) or 2.75A (~42uA per LSB) Continuous on either the high or low side. Wow!

The voltage across the integrated 15 milliohm (.015 ohms!), 0.1% shunt resistor is measured by the internal 16 bit ADC, allowing for measurements over the current range with a resolution of 0.15mA per LSB in high current measurement mode or 42uA per LSB in low current measurement mode.To measure low-side, Connect VIN- to ground and VIN+ to your load's lowest potential. Cut the jumper on the back that connects VBUS to VIN+: VBUS should connect to the highest project voltage, up to 85V. To measure high-side, connect VIN+ to the highest project voltage, and VIN- to the load's highest potential. In high-side measurement, which is most common, we simplify wiring by having a pre-connected jumper from V+ to VBUS.

Usage is simple. Power the sensor itself with 3 to 5VDC and connect the two I2C pins to your microcontroller. Then connect your target power supply to VIN+ and the load to ground to VIN-. We have a detailed tutorial that will do all the gain, range, and math for you - just plug and go with our Arduino library or CircuitPython! You can connect up to 4 sensors on one bus by soldering the address jumpers on the back.

As if that weren't enough, we also added SparkFun qwiic-compatible STEMMA QT connectors for the I2C bus, so you don't even need to solder the I2C and power lines. Simply wire up to your favorite micro using a STEMMA QT adapter cable. The Stemma QT connectors also mean the INA237 can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop.

Comes as a fully assembled breakout board with a 3.5mm terminal block and header. Some light soldering is required to attach the header for use in a breadboard. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
