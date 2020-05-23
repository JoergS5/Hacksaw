# Hacksaw
Arduino, DMxxx and Stepper based hacksaw

design goals:
- driven by Arduino UNO, DM856, a Nema23 Stepper and MeanWell 24V 200W
- endstops for beginning and end of movement
- mechanical construction with aluminium extrusion 45x45 nut 10 based, linear guides
- belt GT2 driven
- saw movement in one direction, lift to avoid teeth destruction into back direction
- controlling vertical force in forward and back movement, Z position of saw
- springs used to avoid stuck movement
- turn workpiece to create groove for locking ring
- bending workpiece slightly to avoid stuck sawing
- best possible precision, avoid burrs if possible

non-goals:
- speed is not important
- quietness is not important
- implementation cost is not important

if possible goals:
- automatic addition and removal of workpieces
- quality check with camera
- measuring the result
