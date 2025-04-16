# OMRON-SYSMAC-motion-library
A library to manage real time cams with multiple segments and multi profiles (Straight, poly3 and poly5). Infinite (modulo) or reciprocal slave profiles management. On-the-fly profile change. Warmstart to recover the position of the slave after a disconnection. Disconnection of the slave with a speed linear regression. Slave starting from null speed and tracking a master in continuous movement (ex. a conveyor). Simples relative or absolute moves done by polynomial generators (avoid MC_MOVE, etc.). Some Standard PLCopen function blocs embedded within the library for simplifying the application writing code.

![cames](https://github.com/user-attachments/assets/b9ffd2e1-940d-4736-a3a2-d0897918b95e)
