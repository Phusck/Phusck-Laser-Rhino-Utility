# Phusck-Laser-Rhino-Utility
Tools for designing laser cut products in Rhino and Grasshopper


All the GH files are inteded to be run with the GrasshopperPlayer Command
(It is possible to setup a Keyboard shortcut for running a specific file)

----
Overlap Fingers.gh
Overlap Fingers Reversed.gh

Will make fingers between X solids(Inner) that overlap with 1 solid(Outer).
It will delete everything involved if there is no overlap.
Usefull anywhere where ends of plates meet.
Reverse will take X Outers and 1 Inner 

----
Halfsies.gh
Halfsies reversed.gh

Will make a make a connection (This must have a name***) between X solids(Inners) that overlap one solid(Outer)
Usefull when to plates overlap, and it is not at the end of the plate.
Reversed version will switch what half belons tho which

----
Lay.gh
Lay - Optimized.gh

Will turn X Solids into 2d laying in a semi optimized plate
OPtimized version is slower but itrerates 5 times instead of 1 on optimizing the space used.


---
Solid Intersections.gh

Will initially write number over overlapping solids in console.
Will Produce the overlapping solids if run to completion.
Usefull for checking if the design is ready to be "layed"
Currently has a bug where it shows "0" before actual number of 

---
Finger 2D.gh


---
Living hinge.gh
