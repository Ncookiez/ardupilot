=====================
||  Flight Modes:  ||
======================

"Drop UGV Here Please"

Descend to specific height based on local zero height.
Slow down to minimum speed based on angle of attack calculations.
Climb back to specific height.

Flight mode can be similar to AutoLand, FBWB or Cruise, but Auto while following a mission would be ideal.

==============
||  Notes:  ||
==============

Local zero needs to be updated based on averages over time to determine actual height instead of GPS height.
Such code might be found in Cruise flight mode.

Speed control algorithm similar to plane.update_fbwb_speed_height() needs to be based on angle of attack.