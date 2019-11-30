# Circular slide rule
A small, circular slide rule suitable for laser cutting.  I've always wanted one of these... so now I've made one.

(c) 2019 Michael Robinson

This work is licensed under the Creative Commons Attribution 4.0 International License. 
To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

## Files included in this repository

The slide rule consists of five separate laser cut files, and require post-processing on a suitably large lathe.

The files included are:
1. The front of the outer ring
2. The back of the outer ring
3. The front of the inner ring
4. The back of the inner ring
5. The index (cut side faces the rings, so that the smooth side faces out)
6. A Jupyter notebook that generates the original SVG files, which were then manually cleaned and formatted for our laser cutter.

## Construction

Cut the index from clear material.

Cut the front side of the two rings on opaque material.  Flip these over in the hole created in the stock (without moving the stock) and print the back.

You will notice that the inner ring does *not* fit the outer ring as laser cut.  This is intentional.  You need to grip both rings (separately) in the lathe and cut them about half-way deep to fit them into each other.  The outer ring gets bored from the back side, while the inner ring gets cut on the front.  The idea is that the inner ring fits in from the back and is held captive by the index and the screw.

