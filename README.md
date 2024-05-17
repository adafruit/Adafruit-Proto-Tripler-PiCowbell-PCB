## Adafruit Proto Tripler PiCowbell for Pico and PicoW PCB

<a href="http://www.adafruit.com/products/5967"><img src="assets/5967.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Proto Tripler PiCowbell for Pico and PicoW. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5967

### Description

The Adafruit Proto Tripler PiCowBell is intended to be treated like a mini solder-less proto plate to simplify programming and sensor or display connectivity for your Raspberry Pi Pico board. Reset button? Yes! STEMMA QT / Qwiic connector for fast I2C? Indeed. Battery with recharging and on/off switch? Affirmative. Built in NeoPixel? Bien sur! EYE SPI connector? Truly! All plug-and-play, so no soldering necessary when used with a Pico H or Pico WH? Here you go!

The Tripler is like if we used a 'Clone Tool' twice on the Proto Under Plate PiCowbell - you get three slots side-by-side, which means you can easily add two 'bell accessories to your Pico or Pico W without soldering on any stacking headers.

LiPoly Battery Charging Support
The Tripler also gives you Lipoly/LiIon support circuitry to take your Pico project on the go. Use any 3.7V/4.2V single-cell Lithium battery with a JST 2-PH connector in the correct polarity. The battery will automagically charge when the Pico is plugged into the USB and switch over seamlessly to battery when USB power is removed.

By default, the charge rate is 500mA for use with 500mAh+ sized batteries. You can cut a jumper to reduce the charge rate to 250mA if using 250mAh to 500mAh battery. So you don't have to unplug the battery often, a slide switch is connected to the Pico Enable pin, so you can disable the Pico's 3.3V power supply completely - this is as close as we can get to 'turning off' the Pico.

Alkaline/NiMH Battery Pack Support
You can also cut a different jumper to disconnect the charger completely from the battery, which means you can use 3xAA or 3xAAA battery packs for alkaline or NiMH battery usage. Of course, you will need an external NiMH charger in that case.

STEMMA QT + EYESPI Connectors

Add sensors and displays in an instant with a 4-Pin JST SH connector that is Qwiic / STEMMA QT compatible for just about any I2C sensor or device we stock. We do not have I2C pullups on the board, but your Qwiic/QT breakout board or accessory likely already has them onboard. If using the Philhower Arduino core, the Wire peripheral is already set up to use IO4 and IO5. If using CircuitPython or MicroPython, you'll need to let the code know to look at 4+5 for SDA+SCL pins.

For colorful high-resolution output, connect any of our EYESPI displays with an 18-pin FPC cable. We connect most of the pins for SPI displays with SD card and touchscreen support. Note that we didn't wire through the Busy or Reset pins so E-Ink displays aren't recommended (they sometimes require those pins for deep-sleep and wakeup)

Double-row Socket Headers
This board has double-row sockets already soldered on; you can plug in your Pico and 'Bell boards directly and access a prototyping area underneath and a second row of socket pins. The second row means you can connect wires just by poking them into the header, either directly to LEDs or buttons or to jumper to a breadboard. So you don't have to look up or count pins; each socket is nicely labeled. There are also 4 mounting holes for easy attachment to an underplate. 

The double-row socket headers we use are 'hollow,' meaning you can connect through the back if desired. Specifically, you can use Pico Stacking Headers to plug into some other device that is expecting Pico pins. Also, in theory, if you soldered pin headers on the 'wrong side' of a Pico, you could plug it up through the bottom.

If you're not mounting this board to something else, we recommend picking up a set of rubber feet to protect your desk.

Features:
* Three 2x20 slim socket headers - plug in your Pico and desired 'Bell and have an extra row of sockets for each pin!
* JST PH connector for LiIon/LiPoly or Alkaline/NiMH battery usage - be sure to cut the "disable charge" jumper to use Alkaline/NiMH batteries.
* LiPoly/LiIon charging circuitry for any 3.7V/4.2V nominal 1-cell battery. Default rate is 500mA, can be set to 250mA by cutting the charge-rate jumper on bottom. Two indicator LEDs let you know if battery is charging (orange) or complete (green)
* Slide switch connected to the Pico Enable pin, which will disable the 3.3V power supply.
* Reset button that sticks out at the end
* JST SH connector for I2C / Stemma QT / Qwiic connection. Or can use it for plain GPIO wiring if you don't have any I2C devices to attach. Provides 3V, GND, IO4 (SDA), and IO5 (SCL)
* There is an extra set of 4 breakout holes next to the JST SH if you want more I2C connections or want to re-assign the I2C port.
* 3 hole-connected strips are in the center areas. You can cut the traces between the holes, but they're intended to be treated like a mini-mini breadboard
* Nearly every pad on the Pico has a duplicate hole pad next to it for solder-jumpering
* The ground pads have white silkscreen rectangles to easily identify, plus one long ground strip near the reset button
* One long strip of connected holes for 3.3V power
* Gold-plated pads for easy soldering

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
