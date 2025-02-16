# Corne V4 Pro-Micro Edition

This version of the Corne V4 is beginner friendly, and brings back the option to make your Corne with whatever microcontroller you want, with the updated V4 layout, which allows wireless support with a Nice!Nano V2, and ultimately save costs when ordering as you DO NOT need PCBA. 

The Corne V4 has a completely new board outline compared to the V3 and V2, and all further development for the Corne will be using the V4 outline.

I designed this board for myself to use, and decided to put it on github, so I apologise if this repository is not fully organised/explained/complete. I do plan on making this repo more organised once I finish university for the year. Feel free to contact me if you need some assistance. reddit: klouderone, discord: klouder#3331

- **Wired and Wireless** Support with the inclusion of battery pads and battery switch
- Pro Micro Footprint Daughter Board Support
- **SMD** and **Through-Hole** diode support
- MX Spaced
- Hotswap **MX and Choc V1** Support
- Breakaway 6th column for 5 column builds
- OLED and Nice!View support
- Waffle Pattern PCB

NOTE: Like all Split Keyboards, NEVER unplug the TRRS interconnect cable while your boards are connected to your computer. 

Please read the entire repo before using anything inside it.

Original Board designed by Foostan, modified By Kea Workshop.

Buy a Kit here https://www.keaworkshop.com/product/corne-v4-pro-micro-edition

https://github.com/foostan/crkbd

![Prebuilt 5 Column Corne](https://github.com/klouderone/cornev4promicroedition/assets/136342173/bbfd555b-4e5a-4ed2-a870-a183a0d69ed6)

![IMG_8871](https://github.com/klouderone/cornev4promicroedition/assets/136342173/901fa39f-69d9-44fd-b6e3-768a6a8b402c)

![image](https://github.com/klouderone/cornev4promicroedition/assets/136342173/598f3457-b834-483d-8778-85fb771b5296)

## Build Guide

**Required Parts**

- 42x Kailh Choc V1 Hot Swap Sockets
- 42x Kailh MX Hot Swap Sockets
- 2x TRRS 3.5mm PJ-320A Audio Jack (not needed for wireless build)
- 42x 1N4148 SOD-123 Diodes
- 2x 3 Pin Toggle Switch (MSK-12C02 & PCM12SMTR)
- 2x Tactile Push Button Switch (3x6x4.3mm)
- 4x Mill-Max Machined 12 Pin Sockets
- 48x Mill-Max Machine Pins
- 2x PH5 4 Pin Female Box Pin Header (for OLED)
- 2x Microcontrollers (Pro Micro, Elite-C or Similar OR Nice!Nano V2)
- 2x Displays (.91 Inch OLED or Nice!View) (optional)
- 42x MX or Choc V1 Switches
- 42x MX or Choc V1 Keycaps
- 1x TRRS Male to Male Cable (if using non-wireless microcontroller)
- 2x Battery (if using a wireless microcontroller like the Nice!Nano V2) 

The build guide is **similar** to the video linked below, except without the LEDs, and the addition of the battery pads and battery switch.

The batteries are intended to be directly soldered to the board, however you can use a PH2 connector on extension leads and route it to the TRRS socket area if you would like to use a battery with a connector. I will change this so that there is also an included connector on the board on the next itteration.

Make sure you are confident will all steps before commencing build as a mistake could result in breaking your microcontroller.

https://www.youtube.com/watch?v=vzDTdLaAzXc

I do plan on making a video on how to build this specific board.

## Cases

The enclosed case uses 7mm M2 standoffs, for both the PCB and the oled covers. 

Ordering/Printing: Each Case has its own folder, and all parts needed for each case are located in that folder. 

Due to the new outline of the corne V4, unfortunately all previous cases are incompatible.

In the cases directory, there are options for a fully enclosed case (pictured), or just a bottom plate with open sides. 

NOTE: due to the placement of the pro micro and TRRS jack, the cases for the v4 on foostans repository are NOT COMPATIBLE with the Pro Micro Edition of the corne v4, as the usb and TRRS jack are blocked by the case as they are specifically placed holes. 

The pro micro edition cases were designed to be as minimalist as possible, so they do have thin parts. This may cause a problem when ordering through JLC, as they have a minimum reccommended thickness of around 1.25mm. I have never had a problem printing all the files myself. 

The enclosed case with folding tenting leg pockets use the following folding legs. https://www.keaworkshop.com/category/components/product/case-tenting-legs

![image](https://github.com/klouderone/cornev4promicroedition/assets/136342173/bd4037fd-9137-4579-877b-2309add871db)
Foostan case above, pro micro edition below.

**NOTE**: The Bolt tenting cases are UNTESTED. I personally have not used them, or will never use them, as I use the enclosed folding tenting feet. Use at your own risk. 

## Firmware 

No external firmware is needed, the same firmware found on the VIAL and QMK repos for the Corne V2 will work for this PCB.

