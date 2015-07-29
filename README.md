A collection of widgets/adapters/breakouts to make prototyping easier.
For more infos please see [**project page on HaD.io**](https://hackaday.io/project/6332-breadboard-widgets)


####ATtiny prog board
Programming board suitable for ATtiny45/85 microcontrollers. Plugs into a breadboards power rails to minimize required space.
USB version pin compatible with uUSB breakout.
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19613-attiny-prog-board)

#####Standard:

<img src="ATtiny prog board/ATtiny prog board.sch.png" alt=".sch" height="300px"><img src="ATtiny prog board/ATtiny prog board.brd.png" alt=".brd" height="300px">

#####With USB:

<img src="ATtiny prog board/ATtiny prog board with USB.sch.png" alt=".sch" height="300px"><img src="ATtiny prog board/ATtiny prog board with USB.brd.png" alt=".brd" height="300px">


####ISP breakout
Simple ISP breakout. Order of pins corresponds to ATmega328 DIP so breakout can be plugged in next to it. Jumper wire required for RST. Also fits ATtiny45/85 with additional jumper for GND.
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19660-isp-breakout)

<img src="ISP breadboard adapter/ISPbreadboardAdapter_ATmega328compatible.sch.png" alt=".sch" height="150px"><img src="ISP breadboard adapter/ISPbreadboardAdapter_ATmega328compatible.brd.png" alt=".brd" height="150px">


####MOSFET breakout
DPAK MOSFET breakout to be used as single channel PWM driver. Footprint should also fit SOT-223 package where pin 2 is internally connected to tab.
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/21781-mosfet-breakout-for-pwm-driver)

<img src="MOSFET breakout/MOSFET breakout.sch.png" alt=".sch" height="200"> <img src="MOSFET breakout/MOSFET breakout.brd.png" alt=".brd" height="200">


####SMD LED breakout
Straight forward SMD LED breakout. See also [**revised button board that can be used as LED breakout**](https://github.com/stefan-lochbrunner/breadboard-widgets/tree/master/button)

#####single
<img src="SMD LED breakout/single_LED.png" alt=".sch" height="100">

#####multi
<img src="SMD LED breakout/multiple_LED.brd.png" alt=".brd" height="200">


####USB breakouts

#####uUSB breakout
Main functionality is to provide "VUSB circuitry" for AVR microcontrollers. Can also be used as generic uUSB breakout by shorting 68R resistor footprints or as breadboard power supply (supplying 5V).
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19615-uusb-breakout)

######v1
<img src="USB/uUSB breakout/uUSB breakout v1.sch.png" alt=".sch" height="150"> <img src="USB/uUSB breakout/uUSB breakout v1.brd.png" alt=".brd" height="150">

######v2
Allows for supplying different voltages by populating the bottom side with desired regulator. For 5V short solder jumper.

superseded by v3

######v3
Allows for supplying different voltages by populating the bottom side with desired regulator. The following modes are possible:

- Supply rail and Vcc pin with 5V directly from USB (regulator not populated, short all 3 pads of solder jumper)
- Supply regulator with 5V from USB which in turn supplies rail and Vcc pin (short center and top pad)
- Supply regulator from rail and get regulated voltage on Vcc pin (short center and bottom pad)

<img src="USB/uUSB breakout/uUSB breakout v3.sch.png" alt=".sch" height="150"> <img src="USB/uUSB breakout/uUSB breakout v3.brd.png" alt=".brd" height="150">

#####USB-B
<img src="USB/USB-B/usb-b.png" alt=".sch" height="150">


####Audio breakouts
Breakout boards for 3.5mm TRS & RCA jacks. [**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/21029-sufs-audio-breakouts)

Based on @sufzoli 's https://github.com/sufzoli/suf-electronics-breadboard

<img src="audio breakout/JACK35/jack35.png" alt=".sch" height="150px"> <img src="audio breakout/RCA/rca.png" alt=".sch" height="150px">

Combined both into single board to save PCB space.

<img src="audio breakout/3.5mm_RCA_breakout.sch.png" alt=".sch" height="150px"> <img src="audio breakout/3.5mm_RCA_breakout.brd.png" alt=".sch" height="150px">


####Button w/ pull resistor
[**more info**](https://hackaday.io/project/6332-breadboard-widgets/log/19614-button-w-pull-updown)

##### single button
Small board that incorporates a button and pull-resistor. Can be plugged into power rails. Depending on which side of a breadboard it is plugged in, acts as pull-up or pull-down. Optional footprints for low-pass filter for debouncing.

<img src="button/single_button.sch.png" alt=".sch" height="150px"> <img src="button/single_button.brd.png" alt=".brd" height="150px">

##### single button with SMD LED breakout
added over complicated LED breakout to utilize board space. Also added arrow to indicate pull direction.

<img src="button/single_button-dual_LED.sch.png" alt=".sch" height="180px"> <img src="button/single_button-dual_LED.brd.png" alt=".brd" height="180px">
