# Level2VPin

Virtual Pinball Cabinet à la Level2

# Bill of Materials (BOM)

## PC Hardware

### Graphics Adaptors

2 nVidia Cards, recent ones, no need for crazy expensive ones. GTX460 1GB at least.

### Power-supply

You will need a 750W supply to be sure the system runs smoothly.

### Mainboard

Robust and compatible Mainboard

### Processor

Any Intel i7

### Speakers

Mid-range 2-speaker setup.

### Monitors

3 are needed in total

* Backbox, head of the cabinet (32")
* Dot Matrix Display (15.6")
* Playfield (46")

For the main playfield the thinner the screen, the better. Mainly because the flipper buttons need to be in the most natural position for game play.

### Memory

2x8GB Ram

### Disk

1xSSD Disk

## Cabinet Hardware

### Electronics

#### Fans

:warning: The cabinet will become hot. Proper cooling is needed. Suggesting 200x200x20 fans. If you want to play it fancy, get fans with LEDs.

#### LED Flashers

These are high-powered LED elements and need passive cooling.

#### Nudge

Nudging a Pinball table is essential to good game-play. 

#### Buttons

We will need quite a few buttons. From the 2 Flipper buttons, 2 Nudge Buttons to the Start buttons and maybe a plunger button.
The [following buttons](http://www.ultimarc.com/ultralux.html) have RGB LEDs pre-wired for the PacLED64

#### iPac

The iPac allows you to control arcade buttons, switches etc through USB. It acts like a keyboard and sends a keyboard signal.
Latency is an issue and I would advise against rolling your own with an Arduino or Raspi.

#### PacLED64

The PacLED64 is an LED controller and lets you connect LED lights.

#### Alternative: LED-Wiz

A more universal piece of hardware that can control many different types of outputs, like solenoids, motors, lights etc.

### Woods

### Misc. Hardware (joints, legs etc.)

4 table legs
1 Coin door

## Software

* Windows 7 Pro (To run XP compatibility mode)
* Visual Pinball
* VPinMAME
* PinballX
* DirectB2S
* Direct Output Framework

# Build

## Precision

Some DIYers suggest a precision of 3mm (for the main screen fitting for example)

# Resources

[Biscuit joiner (Nutfräse)](https://en.wikipedia.org/wiki/Biscuit_joiner)

[Blogger detailing his steps in Building a cabinet](https://vpcabinet.wordpress.com/)

[Virtual Pinball Forums and Software Resources](http://www.vpforums.org/)

[Fractions in inch to mm](http://www.hamuniverse.com/antfrac.html)

## Non-PC Part Vendors

[iPac controllers, LED management and more](http://www.ultimarc.com/)

[Connecting a real Dot-matrix to your PC](http://www.pindmd.com)

[Virtuapin, commercial DIY Cabinets](http://virtuapin.net/index.php?main_page=index&cPath=2&zenid=9361125f7b96c5d60456f6e76a11eb9e)

[Traditional pinball and arcade game parts](http://na.suzohapp.com)

## Pinball Repositories

[OpenGL "Batman" Pinball](https://github.com/loganfsmyth/pinball)

[Pinball Mini for iOS using Cocos2d and Chipmunk (outdated)](https://github.com/adambyram/pinballmini-ios)

[Some notes on building a VPinball Machine](https://github.com/dave-ops/virtual-pinball-machine)

[Helper tool to manage VPin ROMs](https://github.com/jbienz/PinTools)

[DirectOutput framework for virtual pinball cabinets](https://github.com/DirectOutput/DirectOutput)