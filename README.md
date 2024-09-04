# Corne V4 Pro-Micro Edition

This version of the Corne V4 is beginner friendly, and brings back the option to make your Corne with whatever microcontroller you want, which allows wireless support with a Nice!Nano V2, and ultimately save costs when ordering as you DO NOT need PCBA.

The Corne V4 has a completely new board outline compared to the V3 and V2, and all further development for the Corne will be using the V4 outline. This version brings back the Pro Micro footprint so all future cases and development is compatible with a Pro-Micro version PCB.

- **Wired and Wireless** Support with the inclusion of battery pads and battery switch
- Pro Micro Footprint Daughter Board Support
- MX Spaced
- Hotswap **MX and Choc V1** Support
- Breakaway 6th column for 5 column builds
- OLED and Nice!View support

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
- 2x TRRS 3.5mm PJ-320A Audio Jack
- 50x 1N4148 SOD-123 Diodes (extra for mistakes)
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

Make sure you are confident will all steps before commencing build as a mistake could result in breaking your microcontroller.

https://www.youtube.com/watch?v=vzDTdLaAzXc

## Cases

The enclosed case uses 7mm M2 standoffs, and 5mm M2 screws.

NOTE: The tenting cases HAVE NOT been tested yet, though it all works in CAD.

The tenting cases use M6 bolts, with nuts to tent. 4x Bolts of any length, and 8x nuts are required. I have not determined a solution for silicone feet yet, though some sort of putty, or a 3D printed nut on the feet section of the bolt could be used to add feet onto.

Due to the new outline of the corne v4, unfortunately all previous cases are incompatible with the new outline. 

In the cases directory, there are options for a fully enclosed case (pictured), or just a bottom plate with open sides. Note that due to the placement of the pro micro and TRRS jack, the cases for the v4 on foostans repository are incompatible with this version of the corne v4, as the usb and TRRS jack are blocked by the case as they are specifically placed holes.  

The enclosed case with folding tenting leg pockets use the following folding legs. https://www.keaworkshop.com/category/components/product/case-tenting-legs

![image](https://github.com/klouderone/cornev4promicroedition/assets/136342173/bd4037fd-9137-4579-877b-2309add871db)
Foostan case above, pro micro edition below.

## Firmware 

No external firmware is needed, the same firmware found on the VIAL and QMK repos for the Corne V2 will work for this PCB.

