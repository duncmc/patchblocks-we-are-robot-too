We Are Robot Too
================

A generative music patch for [Patchblocks](http://patchblocks.com). Plays a pentatonic scale over an alternating base note and optional sub-bass.

The patch comprises two pulse (square wave) oscillators routed through a low pass filter and a triangle wave (sub bass). Audio is sent to the analogue and digital audio outputs.

* Oscillator 1 plays up and down a pentatonic scale as quarter notes.
* Oscillator 2 also plays quarter notes and alternates between one and two octaves below the tonic note.
* Oscillator 3 plays at tempo three octaves below the tonic note. 

A feedback delay can be applied to the melody (Oscillator 1). Delay time is at double tempo.

Tempo is set to 60bpm within the patch itself.

This patch is base on the original [We Are Robot](https://github.com/duncmc/patchblocks-we-are-robot).

Controls
--------
Left Knob: Set tonic note in range C4 - B4  
Right Knob: Feedback level on the delay  
Left Button: Switch delay on in/out  
Right Button: Switch sub-bass in/out

Left LED indicates delay on/off.
Right LED indicates sub-bass on/off with flashing tempo.

Licence
-------
Licensed under the [GPL v2](http://choosealicense.com/licenses/gpl-v2/) license. A copy is included in this repository.