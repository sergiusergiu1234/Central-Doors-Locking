# Central-Doors-Locking
Embedded system controlling the state of a car's doors.

  Requirements:

1. A remote key allows you to lock, double lock, and open the automobile door.

2. If the doors are currently unlocked, they must be locked when the user pushes the lock switch once for at least 800 ms and releases it again.

3. The lights must flash once with an On-Phase of 300 ms and an Off-Phase of 700 ms to indicate entry into locked mode.

4.If the doors are locked at the time the user pushes and releases his remote key once for 100 to 800 milliseconds, the doors will double-lock.

5.To signify the entry into double-locked mode, the lights must flash three times with an On-Phase of 300 ms and an Off-Phase of 700 ms.

6.If the doors are locked or double-locked, they must be unlocked when the user taps his remote key once for at least 800 milliseconds.

  7.To indicate entering unlocked mode, the lights must flash twice, with an On-Phase of 300 ms and an Off-Phase of 700 ms.

  8. The software's core procedure must run within a 20 ms job.

  9. An LCD display should show the condition of the system and any buttons that have been pressed.
