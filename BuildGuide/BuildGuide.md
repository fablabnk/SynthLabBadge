# BOM

iBom is useful?

CORE

1 x Printed Circuit Board
1 x Lanyard
1 x 9V Battery

FRONT SIDE

BACK SIDE

1 x 9V Battery Clip
1 x 3D printed 9V Battery Mount
2 x M3x8 screws
2 x M3 nuts
1 x 1uF (105) Ceramic Cap
9 x 100nF (104) Ceramic Cap
1 x 22uF Electrolytic Cap
6 x LED 5mm yellow
1 x 1N5817 Diode
1 x PJ-301M 3.5MM Jack Socket (probe, probe in, mix in, out)
1 x 2x5 Pin IDC Eurorack Power Socket
15 x 1k Resistor
2 x 100k Resistor
1 x 10k Resistor
1 x 1.5k Resistor
1 x 470Ohm Resistor
6 x RM-065 1M (105) Trimpot
1 x A100K Potentiometer (surface mount w/ mounting nut)
1 x 8-Pin DIP Socket
1 x LM358 Op-Amp IC
1 x 14 Pin DIP Socket
1 x CD40106 Schmitt Trigger Inverter IC
1 x 5mm photodiode
1 x 3.5mm mono cable

# To Do

Find more spares of
- 1k resistors
- 100k resistors
- 1.5k resistors
Take pliers
104's need more appropriate 3d models (footprint is actually wrong)
Stereo vs Mono Pot

# What's in the bag? Laying out the parts
# Build order

Mistake on board - R6 should read 
Important:
- Add small lengths of wire to kits + battery clips
- Enough 10k spares
- Be sure not to solder resistors in LED holes!
- Don't confuse LEDs and photodiode (latter shows a black square when viewed from top)

BACK: IC sockets and insert ICs (melting risk if done first!)
	- 40106 notch to top
	- LM386 notch to left
BACK: Ceramic capacitors (1 x 105, 8 x 104's)
BACK: Upright resistors
	- from rare to common
1 x 470 Ω: Yellow, Violet, Black, Black, Brown *
1 x 1.5 kΩ: Brown, Green, Black, Brown, Brown *
1 x 10 kΩ: Brown, Black, Black, Red, Brown *
2 x 100 kΩ: Brown, Black, Black, Orange, Brown (1 missing)
15 x 1 kΩ: Brown, Black, Black, Brown, Brown
(check these colour codes)
BACK: 1N5817 Diode
FRONT: 6 x LEDs (not to be confused with photoresistor). Orientation matters!
- insert short leg of LED (cathode, negative) in square pad with flat silkscreening
- insert long leg of LED (anode, positive) in round pad with round silkscreening
- ignore flat and round sides of LED, they're wrong
FRONT: 6 x Trimpots, can only be mounted one way 
BACK: Optional Eurorack components: IDC Header, 22uF cap
BACK: Mount 3 x mono jacks and 1 x pot to back of panel, screwing in at
BACK: Point-to-point wiring
- Vol Pot: 
	- Mount:
		- remove washer and nut
		- mount pot in back of board
		- place washer, then screw on nut from front
		- three pins should point down
	- Solder: wire GND to right pin (?!), WPR to middle pin
- Probe In: T to tip (red), S to sleeve (black)
- Mix In: T to tip (red), S to sleeve (blac)
- Audio Out: T to tip, S to sleeve (mono) and additionally R to (if using stereo connector)
BACK: Attach 3D-printed 9V battery mount.
	- Insert from back and line up holes, ensuring part size matches dotted line
	- Place screws in holes, screw on nuts from front
	- Place 9V battery in the mount, centre it
	- Attach the battery clip to the battery and measure the length of wire needed to go to the 9V Battery holes on the board, leaving a bit extra, cut accordingly
	- Detach the battery clip before soldering. Strip the wire, tin it, insert as follows: 
		- Positive (red) goes to + hole
		- Negative (black) goes to - hole

PROBE: Insert mono 3.5mm jack socket into one end of 3.5mm audio jack cable (helps for stability)
Take photodiode Photodiode (mounted in foam packing)


TEST: Attach 9V battery. Come to audio testing station
BREAKOUT: Use small pliers to break off if using as a badge
LANYARD: attach and wear with pride

# Components with Orientation

Diode
Electrolytic Cap

# Eurorack Components (optional)




# Wiring

Tip vs Sleeve

# Probe Building

Solder photodiode to thonkiconn
- negative (flat side) to sleeve
- positive (round side) to tip

