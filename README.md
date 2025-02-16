# Corne V4 Pro-Micro Edition

This version of the Corne V4 is beginner friendly, adding support of the easier to solder through-hole diodes, with included support for wireless builds, and brings back the option to make your Corne with whatever microcontroller you want, with the updated V4 layout, which allows wireless support with a Nice!Nano V2, and ultimately save costs when ordering as you DO NOT need PCBA. 

The Corne V4 has a completely new board outline compared to the V3 and V2, and all further development for the Corne will be using the V4 outline.

I apologise if this repository is not fully organised/explained/complete.

Please contact me if you find something wrong. reddit: klouderone, discord: klouder#3331, email: claude@keaworkshop.com

## Features

- **SMD** & **Through-Hole** diode support
- **Wired and Wireless** Support with the inclusion of battery pads, battery connector, and battery switch
- Pro Micro Footprint Daughter Board Support
- **MX** Spaced
- Hotswap **MX & Choc V1** Support
- **Breakaway 6th column** for 5 column builds
- **OLED** & **Nice!View** support
- Waffle Pattern PCB

NOTE: Like all Split Keyboards, NEVER unplug the TRRS interconnect cable while your boards are connected to your computer. 

NOTE: Do not use the TRRS jack when also using a battery. ZMK does not support wired splits.

NOTE: Do not use a battery when using wired split. QMK does not support wireless, and the battery may cause damage to your microcontroller.

Please read the **entire repo** before using anything inside it.

Original Board designed by Foostan, modified By Kea Workshop.

Buy a Kit here https://www.keaworkshop.com/product/corne-v4-pro-micro-edition

https://github.com/foostan/crkbd

## Pictures

![Prebuilt 5 Column Corne](https://github.com/klouderone/cornev4promicroedition/assets/136342173/bbfd555b-4e5a-4ed2-a870-a183a0d69ed6)

![IMG_8871](https://github.com/klouderone/cornev4promicroedition/assets/136342173/901fa39f-69d9-44fd-b6e3-768a6a8b402c)

![Screenshot 2025-02-16 211724](https://github.com/user-attachments/assets/6ca276f9-5595-478b-88e8-5b989bc66432)

![Screenshot 2025-02-16 211708](https://github.com/user-attachments/assets/a11322a4-906a-492e-8712-d485264bf1c5)


## Build Guide

**Required Parts**

- 42x Kailh Choc V1 Hot Swap Sockets
- 42x Kailh MX Hot Swap Sockets
- 2x TRRS 3.5mm PJ-320A Audio Jack (if using non-wireless microcontroller)
- 42x 1N4148 SOD-123 Diodes
- 2x 3 Pin Toggle Switch (MSK-12C02 or PCM12SMTR)
- 2x Tactile Push Button Switch (3x6x4.3mm)
- 4x Mill-Max Machined 12 Pin Sockets
- 48x Mill-Max Machine Pins 
- 2x PH5 4 Pin Female Box Pin Header (for OLED)
- 2x PH5 5 Pin Female Box Pin Header (for Nice!View)
- 2x Microcontrollers (Pro Micro, Elite-C or Similar for wired, OR Nice!Nano V2 or similar for wireless)
- 2x Displays (.91 Inch OLED or Nice!View) (optional)
- 42x MX or Choc V1 Switches
- 42x MX or Choc V1 Keycaps
- 1x TRRS Male to Male Cable (if using non-wireless microcontroller)
- 2x Right Angle PH2 Battery Connector (if using a wireless microcontroller like the Nice!Nano V2)
- 2x Battery (if using a wireless microcontroller like the Nice!Nano V2) 

The build guide is **similar** to the video linked below, except without the LEDs, and the addition of the battery pads and battery switch.

The batteries are intended to be directly soldered to the board, however you can use a PH2 connector on extension leads and route it to the TRRS socket area if you would like to use a battery with a connector. I will change this so that there is also an included connector on the board on the next itteration.

Make sure you are confident will all steps before commencing build as a mistake could result in breaking your microcontroller. CHECK, CHECK AGAIN, AND THEN CHECK ONCE MORE.

https://www.youtube.com/watch?v=vzDTdLaAzXc

## Cases

The enclosed case uses 7mm M2 standoffs, for both the PCB and the oled covers. 

Ordering/Printing: Each Case has its own folder, and all parts needed for each case are located in that folder. 

Due to the new outline of the corne V4, unfortunately all previous corne version cases are incompatible.

In the cases directory, there are options for a fully enclosed case, or just a bottom plate with open sides. 

NOTE: due to the placement of the pro micro and TRRS jack, the cases for the v4 on foostans repository are NOT COMPATIBLE with the Pro Micro Edition of the corne v4, as the usb and TRRS jack are blocked by the case as they are specifically placed holes. 

The pro micro edition cases were designed to be as minimalist as possible, so they do have thin parts. This may cause a problem when ordering through JLC, as they have a minimum reccommended thickness of around 1.25mm. I have never had a problem printing all the files myself. 

The enclosed case with folding tenting leg pockets use the following folding legs. https://www.keaworkshop.com/category/components/product/case-tenting-legs

## Firmware 

No external firmware is needed, the same firmware found on the VIAL and QMK repos for the Corne V2 will work for this PCB.

## Changelog

### Revision 1 to Revision 2
- Added support for battery connector
- Added hole for under-board battery support
- Moved OLED headers .5mm lower for easier under microcontroller battery routing.
- Made under microcontroller hole larger
- Added support for through hole diodes
- Moved TRRS jack 2mm lower
- Updated Cases to match revision change
- Diodes have been relocated
- Added TPU sound dampener plate

## Legal

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Revision Control

Rev 1 - Archived 16/02/2025

