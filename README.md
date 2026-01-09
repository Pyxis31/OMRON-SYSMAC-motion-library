# OMRON-SYSMAC-motion-library
A library to manage real time cams with multiple segments and multiple profiles with nodes (master, slave) and types of segments (Straight, poly3 and poly5) defined by program (Structured Text). Automatic calculation of segments linking (speed coefficient only). Infinite (modulo) or reciprocal slave profiles management. Master switchable between internal axis or external position. On-the-fly profile change (at modulo). Warmstart to recover the position of the slave after a disconnection. Disconnection of the slave with a speed linear regression.

A library for tracking a mobile master : slave starting from null speed and tracking a master in continuous movement (ex. a conveyor).

A library for simple polynomial moves (instead of MC_MOVE) for achieving synchronised movements (made by distance + time). With starting and ending edges of moves, settled by timers, to chain movements and so that create for instance, corners on XY trajectory (XY table).

And finally, some standard PLCopen function blocs embedded for simplifying the application writing code.

![cames](https://github.com/user-attachments/assets/b9ffd2e1-940d-4736-a3a2-d0897918b95e)


https://github.com/user-attachments/assets/1d499249-7b2f-4a0f-803b-082d0dd604ab

