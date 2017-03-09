# Standoff board

This board provides an interface between an [analog headstage](https://github.com/gfetterman/analog_headstage) and Intan amplifiers. It is intended for use in small-animal electrophysiology.

The board currently supports 7 channels, matching the analog headstage linked above.

It also provides the option of stepping down a signal to match the amplifiers' input range. The current schematic provides a 62x attenuation, but any resistor pair may be substituted in the voltage dividers during construction. To pass a signal straight through, without attenuation, replace the appropriate resistor (one of R1-R7) with a jumper cable or zero-Ohm resistor, and remove the corresponding grounding resistor (one of R8-R14).
