# N64 Power Supply Repairs

I have worked on 20+ faulty Australian (PAL) 240V N64 PSUs (model number NUS-002 (AUS)). As far as I am aware, two different PSU versions were sold in Australia: the Q96330 and Q96331. The Q96330 appears to be similar to the UK D-63760 with the only difference being the power cord. They are both based on the Matsushita ETYNT184SE / NPY184SE boards. 

## Q96330 
Every faulty Q96330 I have found has been due to one or more open/failed resistors on the daughterboard.
<img width="718" height="364" alt="N64 PSU daughter board with resistor markings" src="https://github.com/user-attachments/assets/3afd834b-882e-402b-bd04-5e00fe3fe626" />

Of the 20 or so PSUs I have repaired, I needed to replace:
- 18 of the 1.5k (1,500) ohm resistors
- 12 of the 220 ohm resistors
- 3 of the 16k (16,000) ohm resistors.

Note, some PSUs required more than one resistor to be replaced. 



### Background
[My Mate VINCE](https://www.youtube.com/@Mymatevince) first published an identification of the issue in [Nintendo 64 - No Power - Can I Repair It?](https://www.youtube.com/watch?v=ZD-0MROz164):
[![Nintendo 64 - No Power - Can I Repair It?](https://img.youtube.com/vi/ZD-0MROz164/0.jpg)](https://www.youtube.com/watch?v=ZD-0MROz164)

The Q96330 uses an ETYNT184SE/NPY184SE board:
<img width="1945" height="953" alt="N64 PSU daughterboard model number" src="https://github.com/user-attachments/assets/c3c91425-005a-4710-83b2-b0a2d3e730af" />
\
\
There is a grey adhesive used to hold still the daughter board to the motherboard. 
<img width="600" height="300" alt="N64 PSU daughterboard adhesive 2" src="https://github.com/user-attachments/assets/ab348641-7bf9-425b-8c65-1a5a0ac95770" />
<img width="300" height="280" alt="N64 PSU daughterboard adhesive" src="https://github.com/user-attachments/assets/7894d33f-c755-4467-8735-59ac4e0e173a" />
\
\
The adhesive is placed over the Schottky barrier diode (D201) which is attached to the heatsink and obviously gets very hot. It is assumed that the heat from the diode package cooks the resistors causing them to fail open. 



## Q96331
I have encountered two different board designs used in the Q96331. They had the following faults:
- 1 had an intermittent fault which exhibited as a shut down 5-60mins after boot. This was rectified by placing thermal paste behind the MOSFET/regulator at DS3 which is close to but not secured to the heatsink. THe lack of fastener appears to be a design oversight.
- 1 had an open thermal fuse (TF1) 
- 1 had an open main fuse (F1) due to a shorted MOSFET (TR1).
  
A good diagnostic guide is available on the Console Mods site: [Power Supply Repair](https://consolemods.org/wiki/N64:Power_Supply_Repair)
