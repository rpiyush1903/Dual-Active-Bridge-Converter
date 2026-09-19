# 3 kW Single-Phase Dual Active Bridge (DAB) Converter for Electric Vehicle Charging

## Description
Electric vehicles are becoming common on Indian roads, and along with them comes a growing need for
good charging infrastructure. Charging can be slow, such as overnight home charging, or fast, at public
stations along highways. The fast and ultra-fast options depend heavily on the power electronic converter
that sits between the grid and the vehicle's battery. This converter has to move a large amount of power
quickly and safely, without wasting too much of it as heat.

This project looks closely at one such converter: the Dual Active Bridge (DAB) converter. A DAB is a
well-established DC-DC converter used for high-power charging because it keeps the vehicle side
electrically isolated from the grid side, it can send power in both directions, and it can be made compact by
running at a high switching frequency. The drawback is that a conventional DAB converter loses power
every time its switches turn on and off, and this loss gets worse as the frequency is pushed higher. This
project set out to reduce that loss through soft-switching techniques, and to build a converter that actually
performs this way in hardware, not only in simulation.

## Goal 
The main objectives of this project were :
• Study about DAB converter 
• Study different DAB converter topologies to see which ones suit EV battery charging best.
• Introduce soft-switching into the DAB converter and check that it genuinely brings down switching
losses.
• Build a laboratory prototype and test it in hardware, rather than relying on simulation alone.
• Design the converter so it can work over a range of input voltages and frequencies, rather than one
fixed operating point.


