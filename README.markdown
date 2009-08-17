Practical Arduino ProtoShield Mega
==================================
Copyright 2009 Jonathan Oxer <jon@oxer.com.au>
Copyright 2009 Mar Alexander <marc.alexander@gmail.com>

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
navigate to Projects -> eagle -> ProtoShield.


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
