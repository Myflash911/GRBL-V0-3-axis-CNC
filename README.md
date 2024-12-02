// Simple 3 axis XY plane gCode interpreter
// Implemented:
// G0 Rapid movement
// G1 Cut movement
// G92 Set position
// M0 Stop (pause)
// M3 Spindle on
// M5 Spindle off
// M17 Enable motors
// M18 Disable motors
// M30 End program (reset)
// T0 Laser
// T1 Engraver (default)
// T? Tools (1-255)
// S? Spindle (?)
// Assumes:
// G17 XY plane only
// G21 Metric
// G90 Absolute coordinates
// G94 mm/min
// Immediate codes:
// ! Pause
// ~ Resume
// % Reset
// ? Status 

https://wokwi.com/projects/416093096601913345
