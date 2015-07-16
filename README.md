A collection of widgets/adapters/breakouts to make prototyping easier.
For more infos please see [**project page on HaD.io**](https://hackaday.io/project/6332-breadboard-widgets)


####ATtiny prog board
Programming board suitable for ATtiny45/85 microcontrollers. Plugs into a breadboards power rails to minimize required space.
USB version pin compatible with uUSB breakout.
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19613-attiny-prog-board)

<img src="ATtiny prog board/ATtiny prog board.sch.png" alt=".sch" height="150px"><img src="ATtiny prog board/ATtiny prog board.brd.png" alt=".brd" height="150px">

####ISP breakout
Simple ISP breakout. Order of pins corresponds to ATmega328 DIP so breakout can be plugged in next to it. Jumper wire required for RST. Also fits ATtiny45/85 with additional jumper for GND.
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19660-isp-breakout)

<img src="ISP breadboard adapter/ISPbreadboardAdapter_ATmega328compatible.sch.png" alt=".sch" height="150px"><img src="ISP breadboard adapter/ISPbreadboardAdapter_ATmega328compatible.brd.png" alt=".brd" height="150px">

####Button w/ pull resistor
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19614-button-w-pull-updown)

##### single button
Small board that incorporates a button and pull-resistor. Can be plugged into power rails. Depending on which side of a breadboard it is plugged in, acts as pull-up or pull-down. Optional footprints for low-pass filter for debouncing.

<img src="button/single_button.sch.png" alt=".sch" height="150px"> <img src="button/single_button.brd.png" alt=".brd" height="150px">

####uUSB breakout
Main functionality is to provide "VUSB circuitry" for AVR microcontrollers. Can also be used as generic uUSB breakout by shorting 68R resistor footprints or as breadboard power supply (supplying 5V).
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19615-uusb-breakout)

#####v1
<img src="USB/uUSB breakout/uUSB breakout v1.sch.png" alt=".sch" height="150"> <img src="USB/uUSB breakout/uUSB breakout v1.brd.png" alt=".brd" height="150">

#####v3
Allows for supplying different voltages by populating the bottom side with desired regulator. The following modes are possible:

- Supply rail and Vcc pin with 5V directly from USB (regulator not populated, short all 3 pads of solder jumper)
- Supply regulator with 5V from USB which in turn supplies rail and Vcc pin (short center and top pad)
- Supply regulator from rail and get regulated voltage on Vcc pin (short center and bottom pad)

<img src="USB/uUSB breakout/uUSB breakout v3.sch.png" alt=".sch" height="150"> <img src="USB/uUSB breakout/uUSB breakout v3.brd.png" alt=".brd" height="150">
