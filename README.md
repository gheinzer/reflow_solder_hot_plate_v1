# Reflow Soldering Hot Plate (v1)
⚠️ This is not finished yet, I've just ordered the parts and I'm now waiting for them to arrive.

## About this project
I have a pretty bad soldering iron at home (it was very cheap and I once bought it in a local store). After trying (and failing) to solder small SMD components to a PCB, I wanted
to find some other solution to this problem.

So I looked at https://github.com/AfterEarthLTD/Solder-Reflow-Plate/ and https://github.com/DerSpatz/PCB-reflow-solder-heat-plate. These projects seem great to me, but they have one downside:
The actual usable, heated area seems to be quite small. And with that, the idea for this project was born.

## Note
I'm an electrical engineering apprentice, so I'm happy to learn about the mistakes I made when designing this :).

## Features
- ❇️ Separate hot plate and driver PCBs
- 🤏 Maximum PCB size: 100.0x100.0 mm (so it's cheap to order from JLCPCB)
- ♨️ Useable heated area for a rectangular PCB: ca. 84.0x73.0 mm
  - I know this is not that great, but the heater PCB can be swapped out independently of the driver. 
- 🔌 24V power supply input
- 📏 4-wire-voltage measurement for the heating element (used to calculate the temperature)
- ⚡ Current measurement and -regulation for variable-speed temperature transitions
- 📟 Built-in LCD display with adjustable contrast
- ↕️ 3 Buttons for navigation
- ⏱️ Theoretically fast heat-up-times (~4A max. heating current)
