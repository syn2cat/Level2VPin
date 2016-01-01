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

Mid-range 2-speaker setup. Or a [Pinball Cabinet Kit](http://virtuapin.net/index.php?main_page=product_info&cPath=17&products_id=70)

Approx. 99€

A complete [Flipper Fidelity Sound System Kit](http://virtuapin.net/index.php?main_page=product_info&cPath=16&products_id=120)

Approx 130€

### Monitors

3 are needed in total

* Backbox/Backglass, head of the cabinet (32") Approx. 300€
* Dot Matrix Display (15.6") Approx. 300€ [in a Kit with USB Interface](http://virtuapin.net/index.php?main_page=product_info&cPath=6&products_id=231)
* Playfield (46") Approx. 1500€ if [Commercial grade used](http://virtuapin.net/index.php?main_page=product_info&cPath=6&products_id=29)

For the main playfield the thinner the screen, the better. Mainly because the flipper buttons need to be in the most natural position for game play.

### Memory

2x8GB Ram

### Disk

1xSSD Disk

## Cabinet Hardware

### Electronics

#### Fans

:warning: The cabinet will become hot. Proper cooling is needed. Suggesting 200x200x20 fans. If you want to play it fancy, get fans with LEDs.

Approx. 20€ a piece

#### LED Flashers

These are high-powered LED elements and need passive cooling.

Approx. 10€ a piece

#### Nudge

Nudging a Pinball table is essential to good game-play. 

#### Buttons

We will need quite a few buttons. From the 2 Flipper buttons, 2 Nudge Buttons to the Start buttons and maybe a plunger button.
The [following buttons](http://www.ultimarc.com/ultralux.html) have RGB LEDs pre-wired for the PacLED64

Approx. 84€ 

#### Plunger

Research if there is a digital "analog" [plunger](http://virtuapin.net/index.php?main_page=product_info&cPath=25&products_id=199).

#### iPac

The iPac allows you to control arcade buttons, switches etc through USB. It acts like a keyboard and sends a keyboard signal.
Latency is an issue and I would advise against rolling your own with an Arduino or Raspi.

Approx. 70€ from [Ultimarc](http://www.ultimarc.com/store/section.php?xSec=2)

#### PacLED64

The PacLED64 is an LED controller and lets you connect LED lights.

Approx. 70€ from [Ultimarc](http://www.ultimarc.com/store/section.php?xSec=5)

#### Alternative: LED-Wiz

A more universal piece of hardware that can control many different types of outputs, like solenoids, motors, lights etc.

### Woods

### Misc. Hardware (joints, legs etc.)

4 table legs
1 Coin door (Approx. 60€ from [Ultimarc](http://www.ultimarc.com/store/section.php?xSec=9&xPage=1&jssCart=3fb4ca3db5c0c8a631d4d777d9515933))

#### Glass

To make the experience more real adding a piece of tempered glass over the big play-field screen is recommended.

## Software

* Windows 7 Pro (To run XP compatibility mode) Approx. 160€
* Visual Pinball
* VPinMAME
* PinballX
* DirectB2S
* Direct Output Framework

# Build

## Reference Pinball

We are very fortunate to have access to a real Pinball Machine.
The machine in question is "The Who's Tommy Pinball Wizard" (January 1994).
[IPDB](http://www.ipdb.org/machine.cgi?id=2579)
[WikiPedia](https://en.wikipedia.org/wiki/The_Who%27s_Tommy_Pinball_Wizard)

## Precision

Some DIYers suggest a precision of 3mm (for the main screen fitting for example)

## Art work

Obviously the Level2 Pinball cabinet wants to be customized with beautiful Art-work. We would need someone to design the outer shell of the cabinet.

# Resources

[Biscuit joiner (Nutfräse)](https://en.wikipedia.org/wiki/Biscuit_joiner)

[Blogger detailing his steps in Building a cabinet](https://vpcabinet.wordpress.com/)

[Virtual Pinball Forums and Software Resources](http://www.vpforums.org/)

[Fractions in inch to mm](http://www.hamuniverse.com/antfrac.html)

## Non-PC Part Vendors

[iPac controllers, LED management and more](http://www.ultimarc.com/)

[Connecting a real Dot-matrix to your PC](http://www.pindmd.com)

[Virtuapin, commercial DIY Cabinets](http://virtuapin.net/index.php?main_page=index&cPath=2&zenid=9361125f7b96c5d60456f6e76a11eb9e)

[Traditional pinball and arcade game parts](https://na.suzohapp.com/)

## Pinball Repositories

[OpenGL "Batman" Pinball](https://github.com/loganfsmyth/pinball)

[Pinball Mini for iOS using Cocos2d and Chipmunk (outdated)](https://github.com/adambyram/pinballmini-ios)

[Some notes on building a VPinball Machine](https://github.com/dave-ops/virtual-pinball-machine)

[Helper tool to manage VPin ROMs](https://github.com/jbienz/PinTools)

[DirectOutput framework for virtual pinball cabinets](https://github.com/DirectOutput/DirectOutput)

# Rough cost-estimate

| Item                  | Price         |
|----------------------|---------------|
| PC-Hardware   | 2300€       |
| Software           | 160€         |
| Screens            | 2100€       |
| Wood                | 1000€       |
| Glass                | 150€         |
| Pinball HW        | 700€         |
| Tools                 | 300€         |
| Misc                   | 120€         |
| **Total Cost**     | **6686€** |

# Comm channels

[Slack](https://level2lu.slack.com/messages/vpinballcabinet/)