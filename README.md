# Central-Doors-Locking
Embedded system controlling the state of a car's doors.

  Requirements:

  1.The car's door can be locked, double locked and unlocked, controlled by a remote key.

  2.When the user presses the lock switch once for at least 800ms and release it again, the doors shall be
locked if the doors are currently unlocked.

  3.Entry into locked mode shall be signaled by flashing the lights once with an On-Phase of 300ms and Off-Phase of
700ms.

  4.When the user presses his remote key once for 100ms to 800ms and release it again, the doors shall be double -
locked if the doors are currently locked.

  5.Entry into double-locked mode shall be signaled by flashing the lights three times with an On-Phase of 300ms and
Off-Phase of 700ms.

  6.When the user presses his remote key once for at least 800ms, the doors shall be unlocked if the doors are
currently locked or double-locked.

  7.Entry into unlocked mode shall be signaled by flashing the lights twice with an On-Phase of 300ms and Off-Phase
of 700ms.

  8.The main routine of the software shall be running within a 20ms task.

  9.Any pressed button and the current system state should be displayed on a LCD display
