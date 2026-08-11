# N64 Rumble Pak
Replication and modification of the Nintendo 64 Rumble Pak PCB.

I first created a schematic of the Rumble Pak when I was repairing a bunch of corroded boards. Many were beyond repair so I decided to create a functionally accurate replica of the original board design. While I was at it, I decided to create a board that draws power from the console and does away with needing batteries (i.e. a custom board for the common battery-free mod).

If you have any comments please feel free to add them to the _Discussions_.
 
## Schematics
### Replica board
[<img width="3500" height="2475" alt="N64 Rumble Pak" src="https://github.com/user-attachments/assets/61b71b3c-afd1-4bf2-9cd0-57c279bd5ab0" />](https://github.com/Ugly-Mug/N64/blob/main/N64%20Rumble%20Pak/N64%20Rumble%20Pak%20v3.pdf)

### Battery-free mod
[<img width="842" height="596" alt="N64 Rumble Pak - Battery free" src="https://github.com/user-attachments/assets/546f6925-e203-4062-8cf4-b1ec47c66b5f" />](https://github.com/Ugly-Mug/N64/blob/main/N64%20Rumble%20Pak/Battery%20Free/N64%20Rumble%20Pak%20-%20Battery%20free.pdf)

## PCB Renders
<img width="500" height="602" alt="N64 Rumble Pak PCB Render Cropped" src="https://github.com/user-attachments/assets/74d6ade2-29f6-48c7-bde7-f5b4eb2c93ef" /><img width="500" height="602" alt="N64 Rumble Pak - Battery free PCB Render Cropped" src="https://github.com/user-attachments/assets/87d47865-1403-4e35-ba3e-8814d0375953" />

## Version history
- v3 schematic: 
	- Corrected direction of diode (D1).
	- Added ground connection for C3 and C4.
	- Removed duplication of R7 (i.e. the resistor between Vcc and A14 marked optional). 
R7 appears to have been added by Nintendo to later board revisions of the Rumble Pak, with earlier revisions using a bodge through-hole resistor.
	- Added approximate capacitance for C1-C4.
	- Added fuse rating for F1.
- v2 schematic: 
	- Improved the layout
- v1
