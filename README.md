# Probe all 3 axes with TLS sensor

UCCNC Macro that let's probe all 3 axes with TLS sensor which in normal case is used for Z only heh :)

see what is is about on your own eyes:
https://youtu.be/X_vFmEGCen4
The TLS (Tool length sensor) is normally used for the Z height probing.
As the TLS is just a plain sensor which sends coordinates anytime it is touched it can be easily used for other axes right?

The changes in the probing macro is not big deal.. see the code and comments
What you need in order turn this concept to reality, is:
- a probe tool. Some kind of screew or something with stopper that defines its length.
- Measure the length and the "probe tool" diameter.
- Update the macro by your own dimensions.
- Test it.
- Ideally measure the air first and have your hand close to E-stop :)
- Once you find the right dimensions you can safely probe.

Note: The macro probes one corner, if you want other corners too, hack the macros from other standart probe corners from the UCCNC screen.
