# PiRelayCase

## Introduction
This is a case designed to hold a Raspberry Pi 3B, 240V relay, 5V PSU, and a couple of ancillary parts. The aim is to allow a 3D printer or CNC router and the associated RPi to be powered from a single socket, and for the power to the tool to be remotely controlled by Octopi or similar.

## Components
Raspberry Pi 3B + x1: 
5V 2A PSU x1: 
240v 5A Relay x1: 
Female-Female Dupont Jumper Cables x8:
Level Shifter: 
IEC Socket:
Single Mains Socket (UK): 
M3 threaded inserts x 10:
Micro-USB power cable x1:
Mains cable for connections (specify diameter):
Veroboard:
Dupont pins - right angle x2
Dupont pins - straight x6 (3x2)
Dupont sockets x2:

## Assembly
..*Download and print one of each STL file. I printed at standard quality, 0.2mm layer height and 30% infill with no supports on a Creality CR10S Pro and got great results.
..* Use a box cutter/deburring tool to trim up the prints and make sure everything drops into the right places in the case.
..* Use a soldering iron to melt the M3 threaded inserts into all the 4mm holes in the case. They should be just flush with the top of the case.
..* Insert your IEC socket into the surround and solder on your mains cables
..* Route your mains cables to the relay and the power socket. Make sure the connection points are well shielded and leave as much space as possible for the 5V wires (though one of the reasons I'm not totally happy with this design is that there will inevitably be some crossover)
..*Clip the RPi clip onto its base plate and install the micro SD card. Probably best to install your software at this point as access to the SD card will be limited later. Make sure you have SSH access as a minimum, as there's no access to the HDMI cable.
..* Solder up your 5V/GND rails using the veroboard and the dupont pins and connect them to the PSU on the 5V side
..* Add in your 5V wiring from the RPi to the level shifter, and from there to the relay and PSU. Then wire the 5V side of the relay to the PSU.
..* Cut the USB cable leaving a short run to go from the PSU to the RPi. Crimp the Dupont sockets onto the end of the positive and negative cables and run these from the 5V/GND rails through the arch to the RPi power socket.
..*The mounting plate for the PSU can be cut to slot the PSU into the grid at a place that makes sense for your build.
..* Secure the PSU with cable ties, and use hot glue/sticky pads to secure the level shifter in the RPI compartment (very professional, I know)
..* Slide the RPi base and PSU base into the case and check all the wire routing
..* Finally, screw down all the lids and check everything works

## Wiring Diagram
TBD

