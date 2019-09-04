# Dualshock4toLive
Max for Live patch that lets you use PS4 controller as MIDI device in Live

11 note on and note off messages. 6 CC parameters.

### Key bindings:
- Square	  	C3
- X		      	C#
- O		    	  D
- Triangle		D#
- L3		    	E
- R3		    	F
- L1		    	F#
- R1		    	G
- Share	    	G#
- Option	   	A
- Pad		    	A#

- L2	    		CC 120
- R2		    	CC 121

Analog sticks are used in combination with arrow keys.

- While holding the Left arrow key, the left analog stick registers left and right movement:  CC 122
- Up arrow, left analog stick up and down movement:                                           CC 123
- Right arrow, right analog stick left and right movement:                                    CC 124
- Right arrow, right analog stick up and down movement:                                       CC 125

### Maping CC in Live
You can map the CC values to any paramenter in Live by using a virtual MIDI adapter (such as IAC driver on Mac), and sending MIDI from a track on which the patch is located to IAC Driver (Bus1).

How to setup a virtual MIDI bus (Ableton website):
> https://help.ableton.com/hc/en-us/articles/209774225-How-to-setup-a-virtual-MIDI-bus
