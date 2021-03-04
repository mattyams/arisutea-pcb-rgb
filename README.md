# Arisutea Keyboard PCB with Modifications and More Modifications
アリステア PCB designed using KiCad. The layout was originally created by FateNozomi, inspired by Lyn's EM7 and TGR Alice with some modification. The layout was then modified by CorruptedJef and robotictomato to add USB-C and shift some keys. This inspired me to modify the layout further by adding the ability to swap your switches out whenever you want and to make some keys a little more permenant. 

Since the layout has been modified yet again I decided to give the project a new name, Arisutea, which translates to Alistair. Obviously keeping the theme running here. 

Key modifications to the PCB:
- Added in Kailh Hotswap sockets
- Addition of full backspace position, connected to switch 59 (row 0, column 13).
- Removed switch 63 to add full backspace position.
- USB-C ESD rework.

Case files are updated to reflect changes to the backspace on switch 59 and can be found here.  Additionaly I have created files for FR4 plates to be made and used with this layout. The plates are designed to fit with the full backspace and I have no clue if it will work on previous revisions. 

Exceprts from original designer, FateNozomi:

Key differences:
- Removed the extra [B] key on the right half and shifted the [NM,.?] row to the left by 0.25U.
- Shifted the 3 keys to the right and added arrow keys.
- Tweaked the bottom so that the 1.5U keys doesn't protrude out a little.

Shifting the [NM,.?] row to the left by 0.25U required quite some work on the arrangement of keys for the right half.
As a result, this does not give the same typing experience as Lyn's EM7 and TGR Alice.
Lyn's EM7 and TGR Alice uses the home row as the center point to vertically align both halves while I used the number row instead.
Due to the nature of staggered keyboards, aligning using the number row resulted in the home row not being aligned.

Disclaimer: Use these files at your own risk.

![Arisutea](https://i.imgur.com/wNgjvPi.png)
![Arisutea-top](https://i.imgur.com/qM8Vc2F.png)

## Gerber Files
Download the gerber and BOM files under [releases](https://github.com/mattyams/arisutea-pcb/releases).

## Assembly
For the components required, you may refer to the bill of materials included along with the release as reference or load up the design file in KiCad.
All the components can be soldered using a regular soldering iron, though soldering the USB-C receptacle might be the biggest hurdle. If needed, the BOM and POS file can be used on JLCPCB to assemble the PCB although I have not used their service I cannot confirm its accuracy. 
