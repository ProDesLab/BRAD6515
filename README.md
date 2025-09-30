# BRAD6515
## Breakout board for the Analog Device SSM6515 Ultra Low Power Class-D Audio Amplifier

The **SSM6515** is one of the smallest and lowest-power amplifiers available on the market.  <br />
**BRAD6515** was created out of the need for a smaller, more handy, and cheaper breakout board than the Analog Device Evaluation Board.  <br />
It was designed to maintain the configuration options offered by the EVB but removing some parts that were not essential for its operation.  <br />
The module is stereo, with two SSM6515 amplifiers.  <br />
The PCB has two 2.54mm pitch 8-pin connectors, compatible with classic breadboards and allowing for quick and easy connection.  <br />

The main power supply is 5V (VIN), while the reference voltage for I2C/I2S can be set to 1.8V or 3.3V (VIO).  <br />
There are two level translators on board to ensure proper operation and voltage compatibility with the external host.  <br />
To slightly simplify the design, the amplifier supply voltage has been set to 1.8V for both PVDD and IOVDD.  <br />

Thanks to the soldered jumpers, it is possible to change the operating mode of the amplifiers.  <br />
The power rails of the two amplifiers have been separated and sectioned using jumpers; this is to allow for more detailed consumption measurements.  <br />
