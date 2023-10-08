# concentric-gear-cutting

This repository contains a tool `mk-gear` to cut concentric gears with an eccentric axis.

The idea is you use a dial indicator to measure the runout of the workpiece,
and then adjust the cutter in/out for each tooth to compensate.

You need to know:

* high reading (what is the highest reading on the dial indicator?)
* low reading (what is the lowest reading on the dial indicator?)
* high reading angle (at what A axis value do you find the high reading?)

The dial indicator should be measuring at **the top** of the part.
The cutting tool should be at **the back** of the part
(so if you take an indicator reading at A90, you'd have to be
at A0 for the same point on the workpiece to be at the cutting tool)

Edit the values in the code.
