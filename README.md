# THIS IS STILL A WIP! NO GUARANTEES ON ANYTHING UNTIL PROTOS HAVE BEEN ORDERED AND TESTED!
- [x] Acrylic Case assembled and tested on original design 03/06/21
- [x] PCBs ordered 03/07/21
- [x] Second Acrylic Case ordered 03/07/21
- [ ] Assemble FR4 Case to original design
- [ ] Assemble Arisutea PCB once received
- [ ] Assemble Acrylic Case to Arisutea design
- [ ] Assemble FR4 Case to Arisutea design
- [ ] Edit QMK firmware for Arisutea design
# Arisutea Keyboard PCB with More Modifications
## Disclaimer: Use these files at your own risk.
アリステア PCB designed using KiCad. The layout was originally created by FateNozomi, inspired by Lyn's EM7 and TGR Alice with some modification. The layout was then modified by CorruptedJef and robotictomato to add USB-C, ESD and to shift/add some keys. This inspired me to modify the layout further by adding the ability to swap your switches out whenever you want and to make some keys a little more permenant. I have designed many boards in the past but never a keyboard so this is my first crack at it and I figured why not go all out? If you notice any issue please open an issue and we can discuss!

Since the layout has been modified yet again I decided to give the project a new name, Arisutea, which translates to Alistair. Obviously keeping the theme running here. 

Key modifications to the PCB:
- Added in Kailh Hotswap sockets.
- Addition of full backspace position, connected to switch 59 (row 0, column 13).
  - Removed switch 63 and repositioned switch 59 to add full backspace position.
- USB-C ESD rework.
- Power LED...just because.
- Updated JSON layout file for this particular keyboard.

![Arisutea](https://raw.githubusercontent.com/mattyams/arisutea-pcb/master/graphics/arisutea-pcb-bottom-3d.png)
![Arisutea-top](https://raw.githubusercontent.com/mattyams/arisutea-pcb/master/graphics/arisutea-pcb-top-3d.png)

# Case Files for Ponoko

Case files are updated to reflect changes to the full backspace on switch 59 and can be found in the hardware folder under [arisutea-case](https://github.com/mattyams/arisutea-pcb/tree/master/hardware/arisutea-case).  The case I ordered with these changes just came in this week (3/6/2021) and it works very well with the changes I made to the full backspace and addition of the stablizer on the prototypes designed by CorruptedJef and robotictomato.

![Ponoko-case-1](https://imgur.com/FcGVhWI.jpg)
![Ponoko-case-2](https://imgur.com/hdUOVdj.jpg)
![Ponoko-case-3](https://imgur.com/IXYp1Ry.jpg)
![Ponoko-case-4](https://imgur.com/iDQcOTm.jpg)

# FR4 Plates and Case

Additionaly I have created files for FR4 plates to be made and used with this layout. These can be found in the hardware folder under [FR4_Plates](https://github.com/mattyams/arisutea-pcb/tree/master/hardware/FR4_Plates). The plates are designed to fit with the full backspace and I have no clue if it will work on previous revisions. These have arrived and are being tested now.

![FR4-Plates-1](https://imgur.com/DepO5uV.jpg)
![FR4-Plates-2](https://imgur.com/oCfGKm7.jpg)
## Exceprts from original designer, FateNozomi:

Key differences:
- Removed the extra [B] key on the right half and shifted the [NM,.?] row to the left by 0.25U.
- Shifted the 3 keys to the right and added arrow keys.
- Tweaked the bottom so that the 1.5U keys doesn't protrude out a little.

Shifting the [NM,.?] row to the left by 0.25U required quite some work on the arrangement of keys for the right half.
As a result, this does not give the same typing experience as Lyn's EM7 and TGR Alice.
Lyn's EM7 and TGR Alice uses the home row as the center point to vertically align both halves while I used the number row instead.
Due to the nature of staggered keyboards, aligning using the number row resulted in the home row not being aligned.

Disclaimer: Use these files at your own risk.

## Gerber Files
Download the gerber and BOM files under [releases](https://github.com/mattyams/arisutea-pcb/releases).

## PCB Assembly
For the components required, you may refer to the bill of materials included along with the release as reference or load up the design file in KiCad.
All the components can be soldered using a regular soldering iron, though soldering the USB-C receptacle might be the biggest hurdle. I have made an adjustment to the USB footprint to allow for a little more error when handsoldering. If needed, the BOM and POS file can be used on JLCPCB to assemble the PCB although I have not used their service I cannot confirm its accuracy or quality.
