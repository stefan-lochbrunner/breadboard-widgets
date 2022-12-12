# uUSB breakout
---------------

Main functionality is to provide "VUSB circuitry" for AVR microcontrollers. Can also be used as generic uUSB breakout by shorting 68R resistor footprints or as breadboard power supply (supplying 5V).
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19615-uusb-breakout)

#### v1
<img src="uUSB breakout v1.sch.png" alt=".sch" height="200"> <img src="uUSB breakout v1.brd.png" alt=".brd" height="200">

#### v2
~~Allows for supplying different voltages by populating the bottom side with desired regulator. For 5V short solder jumper.~~
Superseded by v3

#### v3
Allows for supplying different voltages by populating the bottom side with desired regulator. The following modes are possible:
- Supply rail and Vcc pin with 5V directly from USB (regulator not populated, short all 3 pads of solder jumper)
- Supply regulator with 5V from USB which in turn supplies rail and Vcc pin (short center and top pad)
- Supply regulator from rail and get regulated voltage on Vcc pin (short center and bottom pad)

<img src="uUSB breakout v3.sch.png" alt=".sch" height="200"> <img src="uUSB breakout v3.brd.png" alt=".brd" height="200">
