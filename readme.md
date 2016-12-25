# Basspre MM2

This is an open-source bass pre-amp meant for internal use in active basses with humbucker
inputs.  The circuit is a tribute to the classic 2-band pre-amp used in the
original MusicMan Stingray, with a few modifications.

Board layout and schematic files are in EAGLE format, while the simulations are
done in LT-SPICE.

The pre-amp has a buffered input to maintain very low thermal noise, it uses a rail-splitter IC
instead of a resistor divider to ensure clean tone with very low power, and
the voicing is modified to be less treble-heavy to ensure low EM interference.

[PDF Schematic](schem.pdf)

[OSH Park Link](https://oshpark.com/shared_projects/A13YAxJk)

Here's some simulations and tests of the voicing at various pot positions:

## Flat

### Simulation

![flat](graphs/flat.png)

## Bass Cut

### Simulation

![bass cut](graphs/bass cut.png)

## Bass Boost

### Simulation

![bass boost](graphs/bass boost.png)

### Test

![bass boost](tests/bass boost plot.png)

## Treble Cut

### Simulation

![treble cut](graphs/treble cut.png)

## Treble Boost

### Simulation

![treble boost](graphs/treble boost.png)

### Test

![treble boost](tests/treb boost plot.png)

## Both Boost

### Simulation

![both boost](graphs/both boost.png)

### Test

![both boost](tests/both boost plot.png)

## Both Cut

### Simulation

![both cut](graphs/both cut.png)

### Test

![both cut](tests/both cut plot.png)

Copyright 2014, Russell McClellan, all rights reserved.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Basspre MM-2</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="russellmcc.com" property="cc:attributionName" rel="cc:attributionURL">Russell McClellan</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
