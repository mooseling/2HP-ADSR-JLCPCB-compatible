# 2HP ADSR (JLCPCB Compatible)

This is a fork of kraakenstuff/ADSR, which is a 2HP ADSR envelope generator based on René Schmitz's Fastest Envelope in the West design.

Trying to fabricate this with JLCPCB, I've been running into problems:
- JLC won't do any SMT's on a chip smaller than 10mm. I suppose I could just double up the PCB with some snappable edge cuts. But the board was so close to 10mm I just bumped it to 10mm.
- The PCB has diodes with a 0603 footprint. I haven't been able to find a compatible diode in the JLC library, so I've swapped them to SOD-123 packages and moved things around to make them fit.

Status: Don't know yet! There's a good chance I've messed something up, I'm a noob.

Word up homies

