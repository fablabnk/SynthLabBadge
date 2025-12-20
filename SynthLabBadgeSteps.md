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

8. Build kits

Wait for PCB's/Ali
Test batteries

9. Assemble workshop setup

- effects pedal
- one in Rack 42

# Future

Consider future (self-built) SMT version for cleaner look?
