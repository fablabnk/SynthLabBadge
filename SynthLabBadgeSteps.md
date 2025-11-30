# Noticed that:

- check if we have enough 1.5k resistors (or other values)
	- in case where output of 9V badge runs into 12V badge, we need more boost
- decide on 1 colour or two (probably 1 - blue)
- check lanyard hole against admins badge
- tunable range is quite extreme


# SynthLab Badge Steps

DONE 1. Fix existing design
	a. LED stage:
	- 100k's to 1k's for 6 LEDS
	- 1k's bridged 
	- Q: is 1k resistor on left or right now? In general follow gerbers
	b. First LM358 stage:
	- VCC -> 100k resistor (add) -> tip input (in parallel)
	- change fbk resistor to 10K
	c. Second LM358 stage:
	- Works fine

DONE 2. Update schematic with above changes

Trimpot doesn't feel logarithmic (it's B100K) - should switch for A100K (test in second design)

DONE 3. A/B test with Eurorack vs battery power

DONE 4. Build a second version to ensure above changes are correct/enough

- DONE: Snap first one out as badge
- Be aware that soldering this will give us 1k resistor on right side, as previously
	- other badge omits these completely I think
	- we should try at least one channel with them on left side (as in new schematic)

DONE 5. Rework PCB design, accounting for:

6. Reorder PCBs

- x 20? two different colours?

7. Reorder AliExpress parts

- Lanyards

## BOM

?		1	Lanyard
	- need 20, have 0	
BT1		1	9V Battery
	- need 20, have ?
			Battery Clip
	- need 20, have ?
			Battery Clip Holder (3D Print)
	- need 20, can print 20
			M3x8 screws
	- need 40, have >40
			M3 nuts
	- need 40, have ?
C1		1	1uF (105)
	- need 20, have ?
C2-10	9	100nF (104)
	- need 180, have ?
C11		1	22uF
	- need 20, have ?
D7		6	LED
	- need 120, have 81
D8		1	5817
	- need 20, have <20
J2		1	Probe In 3.5mm Jack Mono (Thonkiconn) w/nut
	- need 20, have plenty
J3		1	Mix In 3.5mm Jack Mono (Thonkiconn) w/nut
	- need 20, have plenty
J4		1	Out 3.5mm Jack Mono or Stereo (Thonkiconn) w/nut
	- need 20 (mono), have plenty
J5		1	Eurorack_Power_10pin_Unshrouded
	- need 20, have 1

R1-19	15	1k
	- need 300, have ?
R3,R20	2	100k
	- need 40, have ?
R4		1	10k
	- need 20, have ?
R6		1	1.5k
	- need 20, have ?
R11		1	470
	- need 20, have ?

RV-7	6	1M (105?)
	- need 120, have 88 - but check drawers
RV3		1	A100K with mounting nut
	- need 20, have 0 (only have B type)

U1		1	LM358
			8 pin DIP Socket
	- need 20, have 20 (including in working badges)
U2		1	CD40106BPWR
			14 pin DIP Socket
	- need 20, have 9			
D1		1	D_Photo
	- need 20, have 17 (19 including existing probes) 

J1		1	Probe Out 3.5mm Thonkiconn
	- need 20, have plenty 
			3.5mm mono cable
	- need 20, have 0

8. Build kits

9. Assemble workshop setup

- effects pedal
- one in Rack 42

# Future

Consider future (self-built) SMT version for cleaner look?