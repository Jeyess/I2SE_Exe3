# I2SE_Exe3
Elevator Shenanigans

Initial "*Rules*":
  1. Passenger selects floor ahead of time (keypad or mobile app)
  2. Safe operations using sensors in the elevator
  3. The elevator count is unknown
  4. The main work is going to be done on the ESP32 microcontroller


ToDo:
  1. Define the optimization problem


Questions:
  - Should the elevator track if new possible passengers are on its path while in motion?
  - Which elevator should handle each request?
  - Would a Stack approach for passengers be more appropriate? to avoid passengers taking too long to disembark.
  - should the elevator avoid going in the opposite direction even if it's faster? as passengers might disembark early because they might think the elevator is broken.
  - How do you calculate whether one allocation is better than another?



Theories:
  - The allocation calculation should take into account the time it would take the elevator to arrive the passenger and the journey time to the destination.
  - 
