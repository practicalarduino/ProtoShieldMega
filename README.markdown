Practical Arduino ProtoShield Mega
==================================
Copyright 2009 Jonathan Oxer <jon@oxer.com.au>  
Copyright 2009 Marc Alexander <marc.alexander@gmail.com>

A general-purpose prototyping shield for the Arduino Mega
microcontroller. Derived from the "Practical Arduino ProtoShield"
design but extended to suit the footprint of the Mega.

This design is intended to maximise prototyping area by extending the
plain pads right to the ends of the board, which also makes it easier
to fit horizontal PCB-mount sockets that need to overlap the edge. Note
that this design uses surface-mount parts in 0805 packaging for
supporting components such as smoothing capacitors, status LEDs, and
associated current limiting resistors.

Features:

 * Reset button wired through to Arduino reset pin
 * Additional momentary button (output biased high by 10k resistor and
   pulled low by the button)
 * Two general-purpose SMT LEDs wired to VCC (drive low to illuminate)
 * Pads for 2 surface-mount 100nF smoothing capacitors


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> ProtoShieldMega.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below. Our intention is that anyone should be free
to use or modify this project for non-commercial use; to distribute the
project under the same terms; and that changes that are made to the
project should also be available under these same terms. However, it may
not be used for commercial purposes without entering into a commercial
license agreement.

What this means in practise is that if you want to make a bunch of PCBs
either personally or by a professional PCB fabrication company for your
own use, go for it. If you want to fab them and give them away, that's
fine too. Or if a group of people (such as members of a hackerspace or
other community group) want to split the costs and have a batch fabbed
to divide between them, that's fine. But if you want to fab boards and
sell them, then you have to obtain a commercial license which will most
likely incur a fee of AU$1 (+GST if applicable) per board fabbed.

In summary: do what you like with it for non-profit use. But if you want
to make money from it, we get a cut too.


LICENSE
-------
This work is licensed under the Creative Commons Attribution-
Noncommercial-Share Alike 2.5 Australia License. To view a copy of this
license, visit

  http://creativecommons.org/licenses/by-nc-sa/2.5/au/

or send a letter to

  Creative Commons  
  171 Second Street, Suite 300  
  San Francisco  
  California, 94105  
  USA


FABRICATION OPTIONS
-------------------
If you haven't had PCBs fabricated before it can be very confusing
trying to work out all the options. We have our boards fabbed by
pcbcart.com, so to save you some hassle the list below shows our
recommended selections for the options on their order form. Some of the
settings can be changed if you have different preferences but this is a
sensible starting point if you don't know what the options mean and
should result in a decent board.

Note that the colour options below are for a yellow board with black
text, and with all exposed surfaces gold-plated for maximum durability.

 * Material:                 FR4
 * Layers:                   2 Layer
 * Material Details:         Standard Tg 140C
 * Part Number:              PA_PROTOSHIELD (or substitute your own)
 * Board Type:               Single Unit
 * Board Size (width):       59.69mm
 * Board Size (height):      53.34mm
 * Quantity:                 Select as appropriate
 * Thickness:                1.2mm
 * Surface Finish:           ENIG (gold)
 * Copper Weight (Finished): 35um
 * Min. Tracing/Spacing:     0.20mm    (8 thou)
 * Min. Annular Ring:        0.30mm    (12 thou)
 * Smallest Holes:           0.40mm
 * Holes Numbers:            300-600
 * Surface Mount:            1 side
 * Soldermask:               Both sides
 * Peelable Soldermask:      None
 * Soldermask Color:         Yellow
 * Matt Color:               None
 * Silkscreen Legend:        1 side
 * Silkscreen Legend Color:  Black
 * Gold Fingers:             No
 * Gold Fingers Number:
 * Gold Fingers Chamfer:
 * Slots in Board:           No Slot in Board
 * Slots quantity in board:
 * Testing:                  Yes
 * UL Marking:               No
 * Date Code Marking:        No
 * Lead Time:                8 or 12 days as you prefer (8 costs more)
 * Special Requirement Note: PCB is routed to outside of Dimension layer
