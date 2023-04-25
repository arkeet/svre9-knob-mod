SVRE9 knob bearing upgrade
==========================

This modifies the knob assembly from a SVRE9 controller to use ball bearings,
similar to Valkyrie Model. It reuses the original shaft, torque limiter, and
encoder bracket.

![Assembly](Images/Assembly.png)

Bill of materials
-----------------

- M3x30 socket head cap screw - 4x
- M3 hex nut, or M3x5x4 (Voron) threaded insert - 4x
- 6x10x3mm flanged bearing (MF106-ZZ or MF106-2RS)
- 8x14x4mm flanged bearing (MF148-ZZ or MF148-2RS)

Print settings
--------------

0.2mm layer height, 4 perimeters, 5 top/bottom solid layers, 40% infill.

Tested with ABS but probably anything is fine.

Assembly
--------

Required tools: 1.5mm, 2mm, and 2.5mm hex drivers

First, disassemble the original knob assembly, but keep the encoder mounted on
the bracket. Before assembling, check that the bearings fit over the shaft
without excessive force. You may need to sand down the shaft slightly to make
it fit.

1. Install the 4 hex nuts or threaded inserts into the top plate.
   Snap the bearings into the printed parts from the top side.
2. Slide the torque limiter onto the shaft, and the shaft into the top plate,
   fitting the torque limiter tabs into the top plate slot.
3. Put the spacer on the shaft, flat face up.
4. Put the knob on the shaft, pressing the whole stack together firmly to
   ensure the bearing and spacer are seated. Secure it with the set screws.
5. Use 4 M3x30 screws to attach the bottom part to the top plate.
6. Install the encoder with its bracket, and secure it with the set screws.

Disclaimer
----------

Copyright 2023 Adrian Keet.

This source describes Open Hardware and is licensed under the CERN-OHL-W v2.

You may redistribute and modify this source and make products using it under
the terms of the CERN-OHL-W v2 (https://cern.ch/cern-ohl). This source is
distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE.
Please see the CERN-OHL-W v2 for applicable conditions.
